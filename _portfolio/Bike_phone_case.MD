---
title: "Adjustable Bike Phone Holder"
excerpt: "A phone holder that mounts on a bike handle bars and fits a range of phone sizes"
header:
  image: assets/img/ufluidics/u_device_side.jpeg
  teaser: assets/img/ufluidics/u_device_side.jpeg

gallery:
  - image_path: assets/img/ufluidics/u_device_side.jpeg
  - image_path: assets/img/ufluidics/u_device_top.jpeg
  - image_path: assets/img/ufluidics/u_mold.jpeg
   
---

# What is Top-Down Modeling?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Top-down modeling is a 3D modeling method that leverages the design of multiple components in a single design file. In traditional CAD modeling, each component is created in its own file and then added to an assembly with all the other components. This can be an effective method for modeling; however, components often need complementary geometry. Top-down modeling makes it extremely easy to reuse detentions from one component in another because all components are in the same workflow. It also eliminates the need to switch between model files to see how changing a single component affects the overall assembly. Traditional CAD modeling can still be useful, especially when used alongside top-down modeling.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Top-down modeling was used to create my bike phone holder because there are six individual parts that need to fit together seamlessly. By using top-down modeling, I was able to create model sketches from previous geometry and add a small offset to account for printing tolerance, making the modeling process significantly easier than if traditional modeling were used.
  
   
# Phone Holder Design:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; There are three main design elements to this phone case: the attachment to the bike, the rotation mechanism, and the phone holder. The attachment mechanism for the bike is relatively simplistic, just consisting of two parts that clamp together on the bike bar. This design is easy to install and adjust, yet very secure when tightened. 

# PHOTO PHOTO PHOTO

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To allow the phone to rotate from portrait to landscape mode, a decent mechanism was included. A picture of the mechanism is below. The slots for the ball allow the case to lock into each position, and the spring holding it keeps it in place. 

# PHOTO PHOTO PHOTO

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The phone holder had to be compatible with a range of phone sizes. This was the most complicated part of the case to model. Several methods were tested to vary the size of the phone case holder, including 3D-printed springs, ratcheting clips, and a threaded rod. Ultimately, the threaded rod was the most reliable option, offering the largest size range. The threaded rod was attached to a solid rectangle with a raised side wall. Another “wall” piece was designed to slide smoothly over the threaded rod, and a bolt was added. When tightened, the bolt squeezes the ‘wall’ against the phone, clamping it in place. 

# PHOTO PHOTO PHOTO

# How to use It:
1. Using M5 bolts, tighten the mounting clamps around the bike handle and adjust the angle to fit your preference.
2. Unscrew the phone clamp bolt enough to fit your phone between the two walls of the clamp
3. Tighten the phone clamp bolt back until your phone is securely held
4. To change between portrait and landscape mode, gently twist your phone until you hear it click into position


![My Image](/EmilySimmons.github.io/assets/img/ufluidics/PFF_application_wheel.jpg){: width="50%" style="display: block; margin: 0 auto;"}


# Printing Technology:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; FFF (Fused Filament Fabrication) was used to make the phone case. Resin printing would have been good for the complicated geometry of the threads. However, given the numerous iterations and deadlines of the project, FFF was the more favorable option due to its accessibility and low prototyping cost. Additionally, the 3D printer with a 4mm nozzle was able to produce well-defined threads. 

# Mold CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811b050cbe17f5f4db6?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="PFF Microfluidic Device" %}

# Sources
* Ashrafizadeh, S. N., Zare, M., & Khatibi, M. (2025). A comprehensive review of pinch flow fractionation in microfluidics: From principles to practical applications. Chemical Engineering and Processing - Process Intensification, 208, 110087. https://doi.org/10.1016/j.cep.2024.110087
* Venzac, B., Deng, S., Mahmoud, Z., Lenferink, A., Costa, A., Bray, F., Otto, C., Rolando, C., & Monflier, R. (2021). PDMS curing inhibition on 3D-printed molds: Why? Also, how to avoid it? Analytical Chemistry, 93(19), 7180–7187. https://doi.org/10.1021/acs.analchem.0c04944

