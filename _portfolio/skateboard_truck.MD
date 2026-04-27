---
title: "Custom Skateboard Truck"
excerpt: "A custom skateboard truck created with generitive design"
header:
  image: assets/img/bike_phone/Assembly_banner.jpg
  teaser: assets/img/bike_phone/Teaser_please_work.jpg

gallery:
  - image_path: assets/img/bike_phone/Assembly_bottom.jpg

   
---

# Design Goal

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The goal of this project was to create a custom skateboard truck that was smaller than a generic one. To achieve this goal, Fusion 360 generative design was used to create a model of the skateboard truck. Two materials - an aluminum alloy (AlSi10Mg) and a stainless steel alloy (17-4 PH) - were tested in the generative design process. In Fusion, a factor of safety of 2 was used, with the minimum mass as the main goal.
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028110a4e996b141fb04f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>{: width="90%" style="display: block; margin: 0 auto;"} <iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811348fa91e1c6b933b?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>{: width="90%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The stainless steel was significantly smaller than the aluminum design. This was expected because, on the whole, stainless steel is much stronger by volume than aluminum. The stainless steel model is 0.11kg heavier than the aluminum one, but it is also 51.5 cubic centimeters smaller, as the aim of this design is to create a small skateboard truck. The stainless steel design was chosen as the better option.

# Load Cases:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To generate the truck designs, load cases had to be applied to the model's fixed components. The model included two shafts for the wheels, a motor mounting plate, and two bodies for mounting the truck (the kingpin and cup). The table below lists the forces added to the model for different situations. The forces for the motor were calculated for an 8lb motor. The forces on the wheels were calculated to be safe for a rider who weighs 297lb. This weight was chosen because it corresponds to the 95th percentile for men in the US.

TABLE

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The motor weight and torque were applied as moment forces to the motor mounting plate, the weight in each of the wheel axils was applied as a bearing force, and friction and the driving force were applied as normal forces to the outer face of each axil. The photo below shows the loads applied for the turn left load case. There was also the force of gravity applied at the center of the model (set to 9.81m/s^2)

![My Image](/EmilySimmons.github.io/assets/img/skateboard_truck/force_applied_example.png){: width="40%" style="display: block; margin: 0 auto;"}


# Generative Design and Powder Bed Fusion Application:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; One example of generative design paired with powder bed fusion is the Formula Racing Team (FRT) at the Budapest University of Technology and Economics (BME). The FRT competes in a competition where they have to design a small open-wheel racing car. The team identified a rocker in their suspension as a component that could benefit from generative design. The initial design of the rocker was laser-cut and assembled from 9 components. Powder bed fusion enabled the part to be created from a single body. This reduces potential failure points at the joints and, when paired with generative design, allows the part to become lighter. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The team used Creo 7.0.2 software to generate six designs (each with slightly different constraints). After analyzing each design and choosing the one that best fit their criteria, the part was printed from a titanium alloy (Ti6Al4V). When printing, the team focused on orienting the part to have the fastest print time while also reducing the number of supports needed.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; After printing, the part had relatively high internal stress. Once the supports were machined off, a large portion of that stress was released, for a stronger part, an additional heat treatment would normally be used. Due to machine limitations, no additional heat treatment was applied to this component.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The team then tested their part to ensure it was dimensionally accurate and could withstand the forces. The team used a laser scanner to measure the part's dimensions, and the measurements closely aligned with the model. They then tested the part statically and dynamically. Static testing showed that the part could withstand approximately 8 times the maximum design load before failure. To dynamically test the part, the team drove approximately 1/5 of the total kilometers during a competition season. They measured the loads on the part, and all were below the design loads; the part sustained no damage during testing. These results confirm the validity of the generatively designed part.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Their use of generative design and powder bed fusion 3D printing allowed them to simplify the complexity and reduce the weight of the custom part in their drive train. 





# Generative Design Discussion:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Generative design is a powerful tool in many applications. It is extremely useful when creating lightweight, custom, and complex components. However, in many cases, it can be overly complicated. To produce a generative design, you need to know exactly where material needs to be, and everywhere that material can not be. Additionally, you need to accurately predict all loads that will be applied to the component. If any component or force is forgotten, the design needs to be regenerated. Components with complex forces acting on them can become problematic if those forces cannot be simplified enough to be easily modeled. On the other hand, if a part is simple, it is often more time-efficient to model it manually. This leaves only the middle area of a moderately complex part that would benefit from weight reduction, where generative design is particularly effective.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; When using generative design, it is important to model all the forces acting on the system. The first step in a generative design should be to identify the forces acting on the system. It could be helpful to draw a free-body diagram, depending on the system's complexity, and identify the forces from it. Another useful step before actually starting generative design modeling is to identify how the forces will affect the system and where additional material is expected. Identifying a general outline of the part's structure lets you check the output model and ensure it makes sense. While a model could still be wrong, this should catch any large errors in the design.


{% include gallery caption="Bike Phone Mount" %}

# Sources
Markovits, Tamás, and Bence Szederkényi. 2022. "Investigation of generative design for powder bed fusion technology in case of Formula Student race car components using Ti6Al4V alloy." Journal of Manufacturing Processes 80:220-231. doi:10.1016/j.jmapro.2022.05.058. 


