---
title: "Microfluidic device: Pinch flow fractionation"
excerpt: "A microfluidic device to sort particles depending on their size"
header:
  image: assets/img/ufluidics/u_device_side.jpeg
  teaser: assets/img/ufluidics/u_device_side.jpeg

gallery:
  - image_path: assets/img/ufluidics/u_device_side.jpeg
  - image_path: assets/img/ufluidics/u_device_top.jpeg
  - image_path: assets/img/ufluidics/u_mold.jpeg
   
---

[![PFF Microfluidic Device](https://img.youtube.com/vi/nTQUwghvy5Q/default.jpg)](https://youtu.be/3i9ZPW2Ylkc)

# What is Pinch Flow Fractionation?

* Pinch flow fractionation (PFF) is a passive microfluidic technique. It is primarily used to sort particles based on their size. It functions by having two inlets: one for the particles and their fluid and one for only the fluid. These two channels converge to the pinch section and the only fluid flow pushes the particles to the wall of the pinch section. The pinch section then turns into the broad section (a much wider channel) and the particles are able to disperse. The smaller particles rise higher than the larger particles because the upward push from the fluid only channel has a larger effect on the lighter particles.
  
   
# PFF Applications:
* PFF has a wide range of applications, as illustrated in the figure below. One interesting application is in environmental surveys. PFF is good for quality control because any contaminant can be separated and recorded from a sample. This concept can be applied to testing water, air, or waste samples. By separating and measuring the particles that compose a sample atypical compositions can be noted and trends over time can be identified.

![My Image](/EmilySimmons.github.io/assets/img/ufluidics/PFF_application_wheel.jpg){: width="50%" style="display: block; margin: 0 auto;"}


# Design
* A symmetric flow design was chosen for this device to minimize the variables that would affect the final location of the particles. The location of the outlets were determined by finding the final height of a 150um and 425um particle (see calculations section for equation used). The values were determined to be 38.9 for a 150um particle and 29.6 for a 450um particle. These were the two extremes of the particle range. The division wall was placed in the middle of these values at 34.4mm from the bottom of the device. Any smaller particles were contained by the top of the device and the larger particles were contained by a second wall.

![My Image](/EmilySimmons.github.io/assets/img/ufluidics/u_calcs.png){: width="50%" style="display: block; margin: 0 auto;"}

* The microfluidic device was designed with a channel width of 650um. This width is 1.3x the width of the largest particle meaning that the particles should not have trouble flowing through or getting stuck in the channels. This also still provides nearly 10mm of separation in the final height for the particles. The channel height is 650um. Channels that are too tall will result in turbulent flow. Finally, the broad section was designed to be as wide and long as possible, because maximizing these values improves the probability of the particles being sorted correctly.
* Integrated flow resistors had not effectively fixed the problem of unequal flow through the outlets and the height of the outlet tubes changing had greatly affected designs in the past. To ensure the correct flow through each outlet I designed a syringe pump system that is able to pull three syringes at individual speeds. By controlling the flow rate of each outlet the flow rate was precisely controlled.

![My Image](/EmilySimmons.github.io/assets/img/ufluidics/IMG_2868.jpeg){: width="50%" style="display: block; margin: 0 auto;"}
  
# Why Resin Printing?
* Resin printing works well for a lower precision, large scale microfluidic device. The minimum feature size for resin printing is around 85um, which is very large for microfluidics. Photolithography is a common manufacturing technique for microfluidic masks because it can achieve very high precision, however, it is very expensive and takes longer to manufacture. Cost and time give resin printed molds an advantage when minimum feature size is not a concern. 

![My Image](/EmilySimmons.github.io/assets/img/ufluidics/u_mold.jpeg){: width="50%" style="display: block; margin: 0 auto;"}
  
# Scaling the Device:
* To increase the particle range the microfluidic device is able to handle, we need to identify what is limiting it. The large particle size is limited by the width of the channel. The small particle is limited by the top of the device as well as the channel width. If the broad section is too short then the smaller particles will collide with the top and not be able to sort between smaller particle sizes. The more challenging limitation is that the channel needs to be wide enough to allow the large particles through, but if it is too large the small particles may clog or not fully be pressed to the top of the pinch section. To try to combat these problems, a multistep sorting device could be designed. By sorting the particles in several pinch flow fractionations, if a particle didn’t reach its calculated height in the first sort section it would have a chance to be restored. Additionally the pinch section width could shrink for the smaller particles, ensuring they are pushed fully to the top of the pinch section.
  
# Manufacturing Instructions

* Create a CAD model for the mold of the microfluidic device
* Resin 3D the mold for the microfluidic device
* Post process the mold by UV post curing and heat cook the mold - cures any uncured resin and reenforces the mold
* Make, cast, and cure PDMS - The PDMS is the actual microfluidic device
* Plasma bond the PDMS to the microscope slide - The plasma bonding causes the slide and PDMS to seal together when put together. This prevents liquid from leaking out the side of the device.
![My Image](/EmilySimmons.github.io/assets/img/ufluidics/Plasma-Treating-Image (1).jpg){: width="30%" style="display: block; margin: 0 auto;"}
* The device is now fully manufactured and ready to be tested.
![My Image](/EmilySimmons.github.io/assets/img/ufluidics/u_device_top.jpeg){: width="50%" style="display: block; margin: 0 auto;"}

# Mold CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811b050cbe17f5f4db6?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="PFF Microfluidic Device" %}

