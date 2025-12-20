---
layout: project
title: Heat Exchanger
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

<img src="../../assets/images/hesetup.png"  width="400"> <br>

I started with testing out the heat exchanger above with a group. We had two liquid reservoirs, a hot one (red) and cold one (blue) that we pumped into the heat exchanger and out to two separate containers. We ran this in both parallel and counterflow at slow and fast speeds to measure the change in temperature of both liquids. 

***Assumptions:*** 
<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- No heat exchange with the surroundings<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Steady State Operation   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- No Work Done   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Potential and Kinetic Energy Negligible   <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Constant Specific Heats   <br>

  Modeled as a control volume around one fluid.

  <img src="../../assets/images/onefluid.png"  width="500">

***Mass Balance Equation:***
<p>
&Sigma; ṁ = 0 = ṁ<sub> in</sub> − ṁ<sub>out</sub>
→ ṁ<sub>in</sub> = ṁ<sub>out</sub>
</p>  
This is true for both the cold and hot fluid. 

***Energy Balance Equation:***
<p>
&Sigma; E = Q̇ - Ẇ + ṁ<sub>in</sub>(h + v²/2 + gz) - ṁ<sub>out</sub>(h + v²/2 + gz) = 0 
<br>
→ 0 = Q̇ + ṁ(h<sub>in</sub> - h<sub>out</sub>)

→ Q̇/ṁ = h<sub>in</sub> - h<sub>out</sub> = c<sub>v</sub>ΔT
</p>  
This is true for both the cold and hot fluid. <br>

***Full Control Volume:***

<img src="../../assets/images/hefullcv.png" width="500">

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

A few changes that we made were switching from parallel flow to counter flow and from a fast to slow flow rate. In parallel flow, the red liquid stayed hotter than the cold liquid at the end whereas the opposite was true with counter flow. I used the constant specific heat of 4184 J/KgK. Looking at when we used the fast flow rate, the parallel flow had the following temperatures: 

<img src="../../assets/images/paralelflow.png" width="500"> <br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * ((34.8+273K)-(50+273K)) = -63.5 kJ/kg

On the other hand, with the counter flow, we saw the following temperatures:
<img src="../../assets/images/counterflow.png" width="500"><br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * ((29.5+273K)-(40+273K)) = -43.9kJ/kg

The fact that the heats started at different temperatures means that I am unable to properly compare the two. So, I am going to analyze our data at the faster flow rates. 

In parallel flow: 
<img src="../../assets/images/pastparallel.png" width="500"><br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * (-(40.9+273K)+(32.5+273K)) = -35.1 kJ/kgK

In counter flow:
<img src="../../assets/images/counter.png" width="500"><br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * (-(40.5+273K)+(20.9+273K)) = -82 kJ/kgK

So, counter flow had a much higher heat transfer out of the hot fluid and into the cold fluid. I believe that this is due to the fact that counter flow has a more efficient heat transfer as it has a greater temperature distance across all the coils of the tubes. 

Additionally, we looked into slow versus fast flow:

With the slow counterflow, 
<img src="../../assets/images/counterflow.png" width="500"><br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * ((29.5+273K)-(40+273K)) = -43.9kJ/kg

With fast counterflow,
<img src="../../assets/images/counter.png" width="500"><br>
Q̇<sub>hot</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * (-(40.5+273K)+(20.9+273K)) = -82 kJ/kgK

So, the fast counterflow had better results than the slow counterflow. It almost doubled the heat transfer rate by increasing the flow rate, while not as dramatic of a change as parallel vs counter flow, it still made a difference. I think this is also a similar reason to the counterflow example, it allows the heat exchanger to maintain a higher temperature difference throughout the heat exchanger.

I decided to look into the heat exchangers on boats for an example of this. While the coolant from a car engine flows through the radiator which uses air flow to cool it down, boats don’t move at fast enough speeds for this to work. Instead, they use a heat exchanger with raw water (water from the ocean or lake). I wanted to use the data from the heat exchanger I used in lab to think about this system. 

I decided to analyze the heat exchanger on a boat with an inboard motor. First, the water is pumped up from the ocean into a filter and into the heat exchanger. The heat exchanger is using the ocean water to cool the engine coolant. 

<img src="../../assets/images/heonboat.png" width="500">

I found a YouTube video of a man with an inboard motor measuring the temperatures of his heat exchanger. With an infrared sensor, he found that in mid June the raw water inlet was 18 degrees Celsius and exiting the system it should reach a maximum of about 35-40. Additionally, when running, a fair assumption for the engine coolant temperature change is 5-11 degrees Celsius with an inlet temperature into the heat exchanger of 80 degrees Celsius. These numbers are based on online research and some more YouTube videos.

***Assumptions:*** 
<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Same as previous assumptions<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Fast counter flow 

I want to see how the heat exchanger would differ in salt water versus fresh water. The specific heat capacity of salt water that I am using is 3993 J/(kg·K) and 4184 J/(kg·K) for fresh water. From the previous energy balance, I know that ṁ<sub>coolant</sub>c<sub>v</sub>ΔT = ṁ<sub>water</sub>c<sub>v</sub>ΔT 
</p>  
I decided to analyze it based on the raw water temperature as I had those concrete values from the youtube video in which he measured the temperatures versus online estimations. 

For fresh water:
Q̇<sub>raw water</sub>/ṁ = c<sub>p</sub>ΔT = 4184 J/kgK * ((35+273K)-(18+273K)) = 71 kJ/kgK

For salt water:
Q̇<sub>raw water</sub>/ṁ = c<sub>p</sub>ΔT = 3993 J/kgK * ((35+273K)-(18+273K)) = 67.9 kJ/kgK

So, while the salt water has slightly lower heat transfer from the coolant into the water, it didn't actually make too much of a difference.

I am interested in ways that the heat exchanger on boats could be improved. One way would be to change the flow rate of the pump, which would require changing the pump but would probably be an easier change based on the fact that the pump is more external than changing the properties of heat exchanger itself. Another, idea would be to change the temperature of the raw water going in, which would require another apparatus on the boat, which is another thing that could be broken, but would help. 

[def]: assets/images/hesetup.pn