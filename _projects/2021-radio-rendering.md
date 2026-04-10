---
layout: project
title: MAE 2250 - ODP
description:  Class Assignment
image: /assets/images/slf.png
---
## Table of Contents
-[Client Outline](#Client-Outline)
-[Functional Protoype](#Functional-Prototype)

# Open Design Project: Spotted Lanternflies (SLFs)  
**Team:** _Sinicus_ 
**Client(s):** _Cornell CALS Extension / E\&J Gallo Winery / National Grape_

## Client Outline
## Problem statement

Our problem of interest is the influx of spotted lanternflies (SLFs) into vineyards from forested areas during peak grape harvesting period, as grapevines are the most attractive host to SLFs after the Tree of Heaven. Thus, our problem focuses on attracting SLFs to something other than the grapevines and eliminating them before they can cause damage to the crop.

## Impact

Preventing SLFs from accessing grapevines decreases the number of throwaway batches and improves the quality of harvests. The accepted tolerance of SLFs in grape products is low, with only 1–2 SLFs per kilogram of grapes required to reject a 22-ton batch. However, a study with mechanical harvesters found that, on average, 300 SLFs from 100-ft of harvesting ended up in bins when not sprayed with pesticides. Eliminating SLFs before they ever reach the vine preserves the integrity of the current crop of grapes, improving the profitability of harvest. Furthermore, SLFs feed on grapevine phloem, reducing nitrogen and carbon in the roots and soil and diminishing the taste and size of future grape harvests. Eliminating lanternflies will preserve the health of the vines, prolong their useful life, and ensure profitability on a longer timescale.

## Proposed direction

Our proposed solution is to attract SLFs away from the vines to then kill them using conventional pesticides. As the SLFs migrate from the Tree of Heaven to the vines, we will aim to attract them to an electrified fence around the perimeter of the vineyard. There, they will be sprayed with pesticides. This solution improves on current methods by applying pesticides away from the vine. As proof of concept, we will develop a section of electrified wire, test that it emits a variety of frequencies that the SLFs may be attracted to, and develop a prototype pesticide sprayer.

## Key Risks / Unknowns

The key risks of focusing on our proposed problem are the scale of the solution required. New
York State has over 30,000 acres of vineyards, and to block SLFs from entering vineyards would
require many resources just to physically cover a lot of space. Furthermore, the use of an electrified wire to attract spotted lanternflies may cause ecological disturbance beyond the desired scope of impact. More specifically, it is possible that other insects (including those beneficial to agriculture such as pollinators) may be attracted to the utilized frequencies and would also be eliminated by the pesticide sprayer. Additionally, it is possible that this electrified wire could pose harm to larger animals passing through areas adjacent to grapevines. Another unknown is how often and for how long pesticides need to be sprayed to be effective.

## Questions for the client

1. How has attracting SLFs been attempted in the past and how successful was it?
2. How long do the pesticides take to kill a SLF and how much is needed to kill one?
3. Would SLFs linger around an alternating electrical current (like moths do around bright lights) as is suggested in some research?

<div style="display:none;">
\newpage
</div>

## Figure

<div style="display:none;">
![](C:\Users\eherr\Documents\fa25-portfolio-eh697\assets\images\odp_figure.jpg "Optional title/tooltip text") 
</div>

<div>
<figure style="text-align: center;">
  <img src="{{ '/assets/images/sprayeritem.png' | relative_url }}"
       alt="odp diagram"
       style="max-width:100%; height:auto;">
  <figcaption>

# Functional Prototype

## Design Intent and Functionality

Our project seeks to mitigate SLF damage in grape vineyards, given that it negatively impacts the grape and wine industry of the Northeastern United States. Our prototype mitigates SLF damage by attracting SLFs to a lure disk and sweeping them into a collection box where they will either die of hunger or be manually eliminated later.

## Design Documentation
<table>
  <tr>
    <th>Part</th>
    <th>Specs</th>
    <th>Fabrication Details</th>
  </tr>
  <tr>
    <td>Wax Fabric</td>
    <td>12 in OD, 5/8in hole in center</td>
    <td>TDS, material from a previous TA. Cut with scissors.</td>
  </tr>
  <tr>
    <td>Disk</td>
    <td>12 in OD, 5/8in hole in center</td>
    <td>TDS wood. Hand sawed the diameter, sanded to round.</td>
  </tr>
    <tr>
    <td>Rake</td>
    <td>Wood Rake: 6in x 3in wood, 9 1.5 in long teeth <br> Metal rake: 6in x 3in wood, 20x 1in long tines</td>
    <td>TDS wood and Malin Co. Galvanized Annealed Gauge .080 wire.</td>
  </tr>
    <tr>
    <td>Crank</td>
    <td>4.5 in long rod with 1 in OD, 2in x 7in wood.</td>
    <td>TDS wood, drill pressed 2 holes to insert axle and handle at ends of the wood.</td>
  </tr>
    <tr>
    <td>Axle</td>
    <td>5/8 in OD</td>
    <td>TDS wood rod, no processing.</td>
  </tr>
    <tr>
    <td>Collection Box</td>
    <td>Base: 6.25in x 6in. Adjusting width for testing.</td>
    <td>TDS wood, sawing machine.</td>
  </tr>
    <tr>
    <td>Disk Stand</td>
    <td>3in x 11in wood, supported by two 3in x 6in wood.</td>
    <td>TDS wood, sawing machine and superglue. Drilled a 1in OD hole to insert an axle about 10in high.</td>
  </tr>
</table>
<br>


## Illustration

<div style="text-align: center;">
  <img src="{{ '/assets/images/odp illustration.jpg' | relative_url }}" alt="Centered Image" style="max-width:100%; height:auto;">
</div>
<br>

## Assembly
<div style="text-align: center;">
  <img src="{{ '/assets/images/odp assembly.jpg' | relative_url }}" alt="Centered Image" style="max-width:100%; height:auto;">
</div>
<br>


## Design Testing Questions
### Rake test
<p><u>Success criterion:</u> The rake implemented in our design must be capable of scraping all eight SLF models placed on the lure disc across six successive trials of two rake revolutions each.</p>
<p><u>Design parameters:</u> Two rake designs were tested. One design consisted of a flat rake with wide, flat teeth with their face normal to the plane of the disc. The other design consisted of metal tines, normal to the plane of the disc, attached to a flat board installed parallel to the face of the disc.</p>
<p><u>Testing results:</u> Eight SLF models were placed on the lure disc at the start of each trial.</p>


<b>Flat Rake</b>
<table>
    <tr>
        <th>Trial #</th>
        <th>SLFs removed from disk</th>
    </tr>
    <tr>
        <td>1</td>
        <td>8</td>
    </tr>
     <tr>
        <td>2</td>
        <td>8</td>
    </tr>
     <tr>
        <td>3</td>
        <td>8</td>
    </tr>
     <tr>
        <td>4</td>
        <td>8</td>
        </tr>
     <tr>
        <td>5</td>
        <td>8</td>
    </tr>
     <tr>
        <td>6</td>
        <td>8</td>
    </tr>
</table>
<br>


<b>Tine Rake</b>
<table>
    <tr>
        <th>Trial #</th>
        <th>SLFs removed from disk</th>
    </tr>
     <tr>
        <td>1</td>
        <td>6</td>
    </tr>
     <tr>
        <td>2</td>
        <td>6</td>
    </tr>
     <tr>
        <td>3</td>
        <td>6</td>
    </tr>
     <tr>
        <td>4</td>
        <td>5</td>
    </tr>
     <tr>
        <td>5</td>
        <td>6</td>
    </tr>
     <tr>
        <td>6</td>
  <td>6</td>
    </tr>
</table>
<br>


<p><u>Conclusion:</u> While the flat rake consistently removed all SLF models from the lure disc, the tine rake consistently failed to do so. This shortcoming of the tine rake mostly arose from the fact that some SLF models became stuck between the metal tines and subsequently could not be scraped off the lure plate.</p>
<p><u>Implication for future design:</u> A design similar to the current tine rake could be problematic because with continued use, too many SLF’s getting stuck in the tines may reduce the effectiveness of the rake. This could be mitigated by making the density of tines larger (resembling a brush more than a rake), making it harder for SLFs to become lodged in between tines. However, this assertion would require further testing. For now, we have determined that the flat rake is preferable for implementation in future prototypes, as it was more successful in achieving the success criterion for this test. An avenue for improvement, however, would be to design a double-sided rake, with the same flat profile as the tested flat rake, but spanning the diameter of the lure plate as opposed to only its radius. We believe that this could make the rake more time efficient by allowing it to scrape a larger area in a given amount of time.</p>




### Stand stability test
<p><u>Success criterion:</u> The stand must be able to support the weight of the crank and axle connected to the disk. The whole assembly must be free-standing. In the prototype, the stand is able to support about 1 pound, and in the final design, the stand will be able to support about 4 pounds. Additionally, the stand should not tip over when placed on an uneven surface at an angle of up to 10 degrees relative to horizontal.</p>
<p><u>Design parameters:</u> Two different axle support systems were tested, one with a separate stand and one with the crank directly fixed to a panel at the back of the collection funnel. The stability of the crank was quantified by measuring the angle of deflection of the rake under gravity. </p>
<p><u>Testing results:</u> The separate crank stand resulted in an angle of deflection of 0 degrees and passed the uneven surface test, while the direct crank attachment resulted in an angle of deflection of 5 degrees and failed the uneven surface test.</p>
<p><u>Conclusion:</u> While the separate stand improved stand stability, a slight height mismatch between the hole in the stand and the hole in the disk prevented clean rotation. Instead of being parallel to the table our prototype rested on, our axle was a bit angled, causing friction during rotation.</p>
<p><u>Implication for future design:</u> A compromise between the separate stand and fixed crank would be to attach the support stand to the collection bin to increase precision in the axle alignment while maintaining the stability of the separate stand design.</p>


### Collection bin test
<p><u>Success criterion:</u> The collection bin should collect at least 85% of the SLFs that are scraped off the disk. </p>
<p><u>Design parameters:</u> 5 different widths of collection bin funnels were tested with both rake designs, and the number of SLFs captured was recorded. 8 SLFs were initially placed on the disk.</p>
<p><u>Testing results:</u></p>


<b>Flat tine rake:</b>
<table>
    <tr>
        <th>Trial #</th>
        <th>OD of funnel (in)</th>
        <th>Funnel OD / Wheel Diameter</th>
        <th>SLFs captured</th>
    </tr>
    <tr>
        <td>1</td>
        <td>7.75</td>
        <td>0.65</td>
        <td>4</td>
    </tr>
    <tr>
        <td>2</td>
        <td>8.50</td>
        <td>0.71</td>
        <td>5</td>
    </tr>
 <tr>
        <td>3</td>
        <td>10.00</td>
        <td>0.83</td>
        <td>7</td>
    </tr>
    <tr>
        <td>4</td>
        <td>11.00</td>
        <td>0.92</td>
        <td>6</td>
    </tr>
    <tr>
        <td>5</td>
        <td>11.00</td>
        <td>0.92</td>
        <td>7</td>
    </tr>
    <tr>
        <td>6</td>
        <td>12.00</td>
        <td>1.00</td>
        <td>7</td>
    </tr>
</table>
<br>


<b>Metal tine rake:</b>
<table>
    <tr>
        <th>Trial #</th>
        <th>OD of funnel (in)</th>
        <th>Funnel OD / Wheel Diameter</th>
        <th>SLFs captured</th>
        <th>SLFs stuck in rake</th>
    </tr>
    <tr>
        <td>1</td>
        <td>7.75</td>
        <td>0.65</td>
        <td>2</td>
        <td>2</td>
    </tr>
    <tr>
        <td>2</td>
        <td>8.50</td>
        <td>0.71</td>
        <td>5</td>
        <td>2</td>
    </tr>
    <tr>
        <td>3</td>
        <td>10.00</td>
        <td>0.83</td>
        <td>5</td>
        <td>2</td>
    </tr>
    <tr>
        <td>4</td>
        <td>11.00</td>
        <td>0.92</td>
        <td>4</td>
        <td>3</td>
    </tr>
    <tr>
        <td>5</td>
        <td>11.00</td>
        <td>0.92</td>
        <td>5</td>
        <td>2</td>
    </tr>
    <tr>
        <td>6</td>
        <td>12.00</td>
        <td>1.00</td>
        <td>5</td>
        <td>2</td>
    </tr>
</table>
<br>
<p><u>Conclusion:</u> The funnel diameter of 10 inches was the smallest diameter to consistently meet the success criteria of collecting 85% of the bugs. Up to 75% of the bugs that escaped the collection bin escaped on the “upswing” of the rake. A further 25% of the escapee bugs landed directly outward from the bin, where the funnel was not extended.</p>
<p><u>Implications for future design:</u> A shield around the sides of the disks should be considered to prevent bugs from rolling off the rake on the upswing and gaining momentum to escape the funnel. Also, a circular funnel design that accounts for bugs falling directly away from the disk should be considered. The trajectory of the bug models was not predictable, and real bugs would introduce even more variation. Therefore, more shield and funnel coverage should be used in future designs.</p>


## Success Criteria


<ol>
    <li>The rake should scrape off at least 80% of the SLFs that land on the disk within 1 revolution.
        <ul>
            <li>The scraping action of the rake is a central component to the lure and trap design. If the rake does not scrape the bugs off the disk, the trap will be ineffective. The effectiveness of the rake can be demonstrated by using the hand crank with bug models placed on the disk and observing the number of models scraped off.</li>
        </ul>
    </li>
    <li>The stand supports the weight of the crank, disk, and rake assembly, at least one pound for the prototype and 4lbs in the final design. Additionally, the trap does not tip over when placed on uneven ground of at most 10 degrees from horizontal.
        <ul>
            <li>We need our stand to support the weight of the assembly to ensure that our project is usable and free-standing. Our project relies on our rake being able to sweep SLFs on the disk downward into the box. We can test this criteria by measuring the deflection of the rake under gravity and as the crank is operated. Also, the stability of the stand can be demonstrated by placing the trap on uneven surfaces.</li>
        </ul>
    </li>
    <li>The collection bin should collect at least 95% of the SLFs that are scraped off the disk.
        <ul>
            <li>The collection bin is important to ensure that the SLFs are contained after being scraped off the disk. If they can just get up and fly away after being scraped off the disk, or if they miss the collection container, the trap will not be effective. This can be easily demonstrated visually with bug models. Watching the bug models fall into the collection bin is also quite engaging. </li>
        </ul>
    </li>
</ol>
<br>