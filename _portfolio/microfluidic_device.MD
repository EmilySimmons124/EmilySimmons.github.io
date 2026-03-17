---
title: "Microfluidic device: Pinch flow fractionation"
excerpt: "A microfluidic device to sort particles depending on their size"
header:
  image: assets/img/lighting_banner2.png
  teaser: assets/img/lighting_banner.png

gallery:
  - image_path: assets/img/lighting_board_heat.png
  - image_path: assets/img/lighting_board_no_heat.png
  - image_path: assets/img/lighting_banner.png
   
---

# What is pinch flow fractionation?

* Pinch flow fractionation (PFF) is a passive microfluidic technique. It is primarily used to sort particles based on their size. It functions by having two inlets: one for the particles and their fluid and one for only the fluid. These two channels converge to the pinch section and the only fluid flow pushes the particles to the wall of the pinch section. The pinch section then turns into the broad section (a much wider channel) and the particles are able to disperse. The smaller particles rise higher than the larger particles because the upward push from the fluid only channel has a larger effect on the lighter particles.

 
# PFF applications:
* PFF has a wide range of applications, as illustrated in the figure below. One interesting application is in environmental surveys. PFF is good for quality control because any contaminant can be separated and recorded from a sample. This concept can be applied to testing water, air, or waste samples. By separating and measuring the particles that compose a sample atypical compositions can be noted and trends over time can be identified.


# Design
*A symmetric flow design was chosen for this device to minimize the variables that would affect the final location of the particles. This allowed me to focus more on trying to maintain equal flow through the ports.  
Integrated flow resistors had not effectively fixed the problem of unequal flow and the height of the outlet tubes changing had greatly affected designs in the past. Because of this I designed an external device to hold the outlet tubes at specific heights. The height each tube was held at was calculated the unrestricted flow through each port and finding the tube height that would balance the flows with the minimum height being ***. This minimum height was chosen because the collection container is **** tall.
*The location of the ports were determined by finding the final height of a 150um and 425um particle (see calculations section for equation used). The values were determined to be 38.9 for a 150um particle and 29.6 for a 450um particle. These were the two extremes of the particle range. The division wall was placed in the middle of these values at 34.4mm from the bottom of the device. Any smaller particles were contained by the top of the device and the larger particles were contained by a second 
wall.
The microfluidic device was designed with a channel width of 650um. This width is 1.3x the width of the largest particle meaning that the particles should not have trouble flowing through or getting stuck in the channels. This also still provides nearly 10mm of separation in the final height for the particles. The channel height is 650um. Channels that are too tall will result in turbulent flow. Finally, the broad section was designed to be as wide and long as possible, because maximizing these values improves the probability of the particles being sorted correctly.


**Bill of Materials**:

| Component      | Price         |
| -------------- | ------------- |
| [2.7kΩ resistor](https://www.digikey.com/en/products/detail/yageo/RC1206FR-072K7L/728657)    | 8× – $0.10    |
| [200Ω resistor](https://www.digikey.com/en/products/detail/yageo/RC1206FR-07200RL/728675)     | 8× – $0.11    |
| [Green LED](https://www.digikey.com/en/products/detail/liteon/LTST-C150KGKT/365085?s=N4IgTCBcDaIDIBUDKCC0BhAjAVgAwGkBxfBEAXQF8g)         | 8x - $1.20         |
| [TRIAC](https://www.digikey.com/en/products/detail/liteon/MOC3063S-TA1/670015)     | 8× – $4.80    |
| [TRIAC](https://www.digikey.com/en/products/detail/stmicroelectronics/Z0109NN-5AA4/725156?s=N4IgTCBcDaIFoAYCMCCcA5dACArAQTwBYQBdAXyA)  | 8× – $4.24    |
| [TRIAC](https://www.digikey.com/en/products/detail/stmicroelectronics/T3035H-8I/9608553?s=N4IgTCBcDaICoGYAMCCsAJAtADgJIgF0BfIA)  | 8× – $24.48    |
| [8 pin terminal block](https://www.digikey.com/en/products/detail/amphenol-anytek/VI0801550000G/2261365)     | 2× – $3.80    |
| [4 pin terminal block](https://www.digikey.com/en/products/detail/amphenol-anytek/VI0401550000G/2261315)     | 2× – $2.02    |
| Custome PCB     | 2× – $5.28    |

\*Quantity and price for one board



# CAD Model
<iframe src="https://duke2531.autodesk360.com/shares/public/SH90d2dQT28d5b602811b5f540c037fd54a7?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
<iframe src="https://duke2531.autodesk360.com/shares/public/SH90d2dQT28d5b6028118eb2abb5d160a809?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Residential Lighting Control System Gallery" %}

