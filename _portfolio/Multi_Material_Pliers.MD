---
title: "Multi Material Pliers"
excerpt: "Multi-material pliers design combining rigid and flexible polymers"
header:
  image: assets/img/Images new/pliers_one.jpeg
  teaser: assets/img/Images new/pliers_one.jpeg

gallery:
  - image_path: assets/img/Images new/handle1_one.jpeg
  - image_path: assets/img/Images new/handle1_three.jpeg
  - image_path: assets/img/Images new/handle1_two.jpeg
  - image_path: assets/img/Images new/handle2_one.jpeg
  - image_path: assets/img/Images new/handle2_three.jpeg
  - image_path: assets/img/Images new/handle2_two.jpeg
  - image_path: assets/img/Images new/pliers_one.jpeg
  - image_path: assets/img/Images new/pliers_two.jpeg
  - image_path: assets/img/Images new/spring_two.jpeg
  - image_path: assets/img/Images new/spring_one.jpeg
  - image_path: assets/img/Images new/plug_one.jpeg
  - image_path: assets/img/Images new/plug_two.jpeg
  - image_path: assets/img/Adobe Express - Pliers_latching_seitch.gif
  - image_path: assets/img/Adobe Express - Pliers_surface_mount_LED.gif
  - image_path: assets/img/Adobe Express - Pliers_motion.gif


   
---

# 3D Printing Background
Print in place 3D printing refers to parts that are fully functional immediately after removal from the printer, requiring little to no post-processing. Common examples include trinkets, such as flexible dragons, but this technique can also be applied to functional mechanical components.

3D printing provides a relatively low-cost method for prototyping complex parts. While it is generally slower and less economical than traditional subtractive manufacturing for large-scale production, it occupies an important niche for iteration. Currently, multi-material 3D printers are not sufficiently affordable or efficient for widespread manufacturing use, which limits the practicality of print-in-place designs in many applications.

Print-in-place parts are further constrained by material compatibility, particularly in multi-material designs. Achieving a strong bond between two different thermoplastics can be challenging; in many cases, the materials must have similar surface chemistry to bond effectively during printing. This requirement significantly restricts the combinations of materials that can be used in a single printed part and complicates the design of durable multi-material mechanisms.

# Project Goals
The goal of this project was to design and fabricate a functional pair of pliers using two different filament materials. Based on existing examples of 3D-printed pliers, many of which have a very limited jaw range, an additional design goal was to ensure the pliers could grasp a wide range of object sizes.

There were two possible approaches to fabricating the pliers: print in place or printing the components as separate parts. Due to limited access to a multi-material 3D printer, the components were printed separately. However, the pliers were still designed to be compatible with a multi-material printer, allowing for fabrication as a single print.



# Plier Design

* The pliers were designed to be easily assembled and allow for individual components to be replaced. The pliers are composed of four components: two handles, a spring, and a cap. All the components are a press fit together with the cap providing an extra layer of security to hold the spring in place. 
* All the components except the spring are printed from PETG for strength. The spring is printed with TPU to allow it to flex when the pliers are used. The spring is designed as two circles connected by small spokes - similar to a bike wheel. When the pliers are closed the spokes elasticity deforms with the rotation and once pressure is released the spokes return to their initial position, keeping the pliers in an open position when not in use.
*Another main design consideration was balancing plier size with jaw size. In order to pick up larger objects the spring has to deform more and be larger. The current jaw size is 21mm. However, because the spring plasticly deforms in both directions it is possible to pick up larger objects. The length of the jaws could also be increased to make the jaw size larger. For this specific project this jaw size is sufficient and keeping the spring and jaw length the size they are allows the pliers to be more compact. 
*Additional adjustments could also be made to the handles. They are currently 95mm long and 25mm wide. Modifying these values could allow for higher torque or a better in hand fit for different users.


**Print Slicer Settings**:

| Settings      |  [TPU](https://us.polymaker.com/products/polyflex-tpu95?variant=39574341681209)         | [Hyper PETG](https://store.creality.com/products/hyper-series-petg-3d-printing-filament-1kg)         |
| -------------- | ------------- | ------------- |
| Nozel Temperature| 220°C    | 250°C    |
| Bed Temperature| 40°C    | 70°C    |
| Layer Height | 0.2mm    | 0.2mm    |
| Infill Type| Rectilinear    | Grid    |
| Infill Percent| 100%    | 15%    |


\*Creality Print 7.0 Slicer



# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028112fefa199451c7020?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


{% include gallery caption="Plier Gallery" %}

# Sourses
*Pereira, A. C., Bártolo, P. J., & Vázquez Martínez, J. M. (2023). Sustainability perspectives: A review of additive and subtractive manufacturing. Sustainable Manufacturing and Service Economics, 3, 100050. https://doi.org/10.1016/j.smsce.2023.100050
*Yoon, H.-S., Lee, T.-M., Kim, H.-S., Min, B.-K., Kim, M.-S., Kim, N.-N., & Ahn, S.-H. (2015). A comparison of energy consumption in bulk forming, subtractive, and additive processes: Review and case study. International Journal of Precision Engineering and Manufacturing–Green Technology, 1(3), 261–279. https://doi.org/10.1007/s40684-014-0033-0
*Kim, H., Park, E., Kim, S., Park, B., Kim, N., & Lee, S. (2017). Experimental study on mechanical properties of single- and dual-material 3D printed products. Procedia Manufacturing, 10, 887–897. https://doi.org/10.1016/j.promfg.2017.07.076

