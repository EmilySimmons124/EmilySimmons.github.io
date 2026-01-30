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

gallerytwo:
  - image_path: assets/img/Adobe Express - Pliers_motion.gif
  - image_path: assets/img/Adobe Express - Pliers_latching_seitch.gif
  - image_path: assets/img/Adobe Express - Pliers_surface_mount_LED.gif


   
---

# Print in Place 3D Printing



# Plier Design

* The pliers were designed to be easily assembled and allow for individual components to be replaced. The pliers are composed of four components: two handles, a spring, and a cap. All the components are a press fit together with the cap providing an extra layer of security to hold the spring in place. 
* All the components except the spring are printed from PETG for strength. The spring is printed with TPU to allow it to flex when the pliers are used. The spring is designed as two circles connected by small spokes - similar to a bike wheel. When the pliers are closed the spokes elasticity deforms with the rotation and once pressure is released the spokes return to their initial position, keeping the pliers in an open position when not in use.
*Another main design consideration was balancing plier size with jaw size. In order to pick up larger objects the spring has to deform more and be larger. The current jaw size is *****. However, because the spring plasticly deforms in both directions it is possible to pick up larger objects. The length of the jaws could also be increased to make the jaw size larger. For this specific project this jaw size is sufficient and keeping the spring and jaw length the size they are allows the pliers to be more compact. 
*Additional adjustments could also be made to the handles. They are currently 95mm long and 25mm wide. Modifying these values could allow for higher torque or a better in hand fit for different users.

{% include gallerytwo caption="Plier Motion Gallery" %}

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

