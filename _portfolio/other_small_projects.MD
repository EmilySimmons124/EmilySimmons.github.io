---
order: 9
title: "Other Small Projects"
excerpt: "A collection of smaller projects, including a custom phone case, a microfluidic mold, a self-flying drone, horse jumps, and a light switch locator light"
header:
  image: assets/img/other_projects/collage_banner.jpg
  teaser: assets/img/other_projects/collage_thumbnail.jpg

gallery:
  - image_path: assets/img/other_projects/phone_back.jpg
  - image_path: assets/img/other_projects/phone_front.jpg
  - image_path: assets/img/other_projects/phone_back2.jpg
  - image_path: assets/img/other_projects/phone_front2.jpg
  - image_path: assets/img/other_projects/phone_bottom.jpg
  - image_path: assets/img/other_projects/phone_camera_covers.jpg
  - image_path: assets/img/other_projects/phone_prototypes.jpg
  - image_path: assets/img/other_projects/mold_cad_angle.jpg
  - image_path: assets/img/other_projects/mold_cad_top.jpg
  - image_path: assets/img/other_projects/mold_cad_channels.jpg
  - image_path: assets/img/other_projects/mold_printed.jpg
  - image_path: assets/img/other_projects/drone_ground.jpg
  - image_path: assets/img/other_projects/drone_flying.jpg
  - image_path: assets/img/other_projects/jump_pvc.jpg
  - image_path: assets/img/other_projects/jump_wood.jpg
  - image_path: assets/img/other_projects/switch_circuit.jpg
  - image_path: assets/img/other_projects/switch_glow.jpg

---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This page collects several smaller projects I have completed through research, school, and at home.

# Custom MagSafe Phone Case

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I designed and 3D printed a custom case for my own phone that protects it without getting in the way of the MagSafe wallet I use every day.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_back.jpg){: width="50%" style="display: block; margin: 0 auto;"}

**Design Goals**:

* **MagSafe compatible.** The back of the case is only 1.2mm thick. Apple allows up to 2.1mm, but in testing my wallet was not held securely at 1.8mm.
* **Easy-to-press buttons.** Design 1 uses separate button inserts that can be customized in color and material, while Design 2 builds the buttons into the case for a better fit.
* **Secure fit.** The case matches my phone's exact dimensions, with a 1.75mm lip over the screen and slight compression on the sides. The profile dimensions were modeled parametrically so the fit was easy to adjust between prototypes.
* **Flexible material.** Printing in TPU makes the case easy to put on and take off, absorbs shock, and makes up for small fit errors, though TPU prints slowly and is prone to stringing.
* **Personal style.** A textured build plate gives the back a bumpy finish, the buttons, camera protector, and WHHFBK insert (a family motto) are printed in dual-color PLA, and the back has a heart pattern.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_bottom.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The case went through two prototypes before the final design. The first prototype fit well but needed larger button holes, a taller camera cover with more taper, and a thinner back for a stronger MagSafe hold. The second added the WHHFBK insert, and the final version deepened the button holes, added a version with built-in buttons, and added the heart pattern.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_prototypes.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Fusion 360 model of the phone case is embedded below.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028110b07d76ca583ad7a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>{: width="90%" style="display: block; margin: 0 auto;"}

---

# Microfluidic Mold for Bacteria Testing

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; While volunteering in the Payne Lab, a biochemistry lab at Duke University, one of my projects was to improve the lab's ability to use microfluidic devices. Microfluidic devices are used to test how different materials and organisms interact. Their small size offers many benefits, but it also makes them difficult and costly to manufacture. 3D printing the molds for these devices can be a much more economical option.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_cad_angle.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The design included many small side channels attached to a main channel. The side channels were designed to trap bacteria, allowing us to test how the bacteria respond to being immersed in different mediums. The channels are only 5 microns thick, which made 3D printing the mold challenging. I designed the model in Fusion 360 and printed it at Duke University.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_cad_channels.jpg){: width="30%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The design went through several iterations, including adding indicators for where to insert the supply tubes, adjusting the size and spacing of the side channels, and refining the ends where the tubes for adding and removing different mediums are inserted. The final mold can be easily cast and is more affordable and easier to use than commercial microfluidic devices.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_printed.jpg){: width="40%" style="display: block; margin: 0 auto;"}

---

# Self-Flying Drone

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In my high school robotics class, my partner and I spent a semester building and programming a self-flying drone. Because of our class's limited budget, we purchased an inexpensive drone kit along with several sensors to track the drone's location.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/drone_ground.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A GPS module, mounted on a plate above the drone to prevent interference, tracked the drone's position, and a Navio2 flight controller guided it along a preplanned path. The drone could take off, fly the route, and land without any human input. Because of the project's short timeframe, many components were quickly attached to the drone. With more time, I would make the design more robust and improve its appearance.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/drone_flying.jpg){: width="30%" style="display: block; margin: 0 auto;"}

---

# Horse Jumps

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Horse jumps, like most horse equipment, are extremely expensive; a single jump can cost over $1,000. Instead of buying them, I designed and built my own. The jumps needed to adjust to a wide range of heights, be durable enough to be left outside for long periods of time, and be lightweight and easy to move.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/jump_pvc.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The jumps use square PVC for the body and a wood base. To build them, I measured and marked each drilling location and used a drill press to keep every hole straight. I then built a wood support to create a strong base for the PVC to slide over. I also built a shorter set that uses wooden posts instead of PVC.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/jump_wood.jpg){: width="40%" style="display: block; margin: 0 auto;"}

---

# Light Switch Locator Light

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Finding light switches in the dark can be challenging, so I created a small light that attaches to the back of a light switch cover and gives off just enough light to easily locate the switch.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; My first version was simply a resistor and an LED wired together and hot-glued onto the switch cover. I then designed a mini custom PCB with a surface-mount LED, a resistor, and a power connector and glued it onto the back of the cover. Moving to a custom PCB made the circuit smaller and cleaner than the hot-glued prototype.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/switch_circuit.jpg){: width="30%" style="display: block; margin: 0 auto;"}
![My Image](/EmilySimmons.github.io/assets/img/other_projects/switch_glow.jpg){: width="30%" style="display: block; margin: 0 auto;"}

{% include gallery caption="Other Small Projects" %}
