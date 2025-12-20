---
layout: project
title: Analysis of Heat Exchanger
description: ENGRD 2210 with Heat Exchanger
image: /assets/images/heatexchangerdiagram.png
---
<!--
<div style="display: flex; gap: 15px;">
  <img src="/assets/images/hesetup.png" style="width: 48%;">
  <img src="/assets/images/hecrosssection.png" style="width: 48%;">
</div>
-->
#### Heat Exchanger 

For ENGRD 2210 (Thermodynamics), we were asked to analyze a device that we have studied in class. I chose to look into a heat exchanger.  

A heat exchanger has two fluids flowing past each other many times in either parallel or counterflow to allow heat transfer between the two fluids without mixing. 

<div class="image-row">
  <img src="/assets/images/hesetup.png">
  <img src="/assets/images/hecrosssection.png">
</div>

I started with testing out the heat exchanger above with a group. We had two liquid reservoirs, a hot one (red) and cold one (blue) that we pumped into the heat exchanger and out to two separate containers. We ran this in both parallel and counterflow at slow and fast speeds to measure the change in temperature of both liquids. 

***Assumptions:*** 
<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- No heat exchange with the surroundings<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Steady State Operation   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- No Work Done   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Potential and Kinetic Energy Negligible   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Constant Specific Heats   <br>

  Modeled as a control volume around both fluids.
  <br>
<img src=/assets/images/mydrawing.png>

***Mass Balance Equation:***
<p>
&Sigma; ṁ = 0 = ṁ<sub> in</sub> − ṁ<sub>out</sub>
→ ṁ<sub>in</sub> = ṁ<sub>out</sub>
</p>  
This is true for both the cold and hot fluid. 

***Energy Balance Equation:***<
<p>
&Sigma; E = Q̇ - Ẇ + ṁ<sub>in</sub>(h + v²/2 + gz) - ṁ<sub>out</sub>(h + v²/2 + gz) = 0 
<br>
→ 0 = Q̇ + ṁ(h<sub>in</sub> - h<sub>out</out>)

→ Q̇/ṁ = h<sub>in</sub> - h<sub>out</sub> = c<sub>v</sub>ΔT
</p>  
This is true for both the cold and hot fluid. <br>

***Full Control Volume:***

<img src=/assets/images/hefullcv.png>
Looking at it as a full control volume system, the energy balance equation is: 
<p>
&Sigma; E = Q̇ - Ẇ + ṁ<sub>cold in</sub>(h + v²/2 + gz) - ṁ<sub>cold out</sub>(h + v²/2 + gz) + ṁ<sub>hot in</sub>(h + v²/2 + gz) - ṁ<sub>hot out</sub>(h + v²/2 + gz)= 0 
<br>

→ 0 = ṁ<sub>cold</sub>(h<sub>in</sub>-h<sub>out</sub>) + ṁ<sub>hot</sub>(h<sub>in</sub>-h<sub>out</sub>)
<br>

→ ṁ<sub>cold</sub>(h<sub>in</sub>-h<sub>out</sub>) = ṁ<sub>hot</sub>(h<sub>in</sub>-h<sub>out</sub>)
<br>

→ ṁ<sub>cold</sub>c<sub>v</sub>ΔT = ṁ<sub>hot</sub>c<sub>v</sub>ΔT 
</p>  





