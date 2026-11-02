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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I designed and 3D printed a custom case for my own phone. Phone cases are constantly in demand: in 2024, 91% of Americans owned a smartphone [1], and 86% of iPhone users report using a case [2]. Because Apple and Samsung release new phones every year, the phone case industry must constantly adapt to new models and trends to create a sellable product.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_back.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; My main design goal was to protect my phone while keeping full MagSafe functionality. The MagSafe wallet on the back of my phone means I do not have to carry a separate wallet, so if the case did not work with it, I would never use the case. Apple specifies a maximum back thickness of 2.1mm for MagSafe to work, but in testing I found that at 1.8mm the magnet was relatively weak and my wallet was not held securely. The back of the final case is only 1.2mm thick.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The second major consideration was how to easily press the buttons on the side of the phone. The simplest solution would be cutouts that let you press the buttons directly, but that would be less accessible, so I designed two solutions. Design 1 uses separate button inserts, which are easy to press and can be customized in color and plastic type, but they can affect the fit of the case if they are not designed perfectly. Design 2 builds the buttons into the case, which gives a better fit, but the buttons are slightly harder to press and cannot be customized. Design 1 is shown first below, followed by Design 2.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_front.jpg){: width="50%" style="display: block; margin: 0 auto;"}
![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_front2.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The case was designed to the exact dimensions of my phone, with a lip that extends 1.75mm over the front of the screen. This sizing holds the phone in place with the lip and slight compression on the sides while keeping the lip small enough that it does not interfere with the touch screen. Because 3D printing tolerances depend on many factors, like the printer, material, and print settings, I modeled the profile dimensions (thickness, length, and width) parametrically. If a prototype did not fit, I could quickly identify and resize the feature that needed to change while the rest of the case stayed intact.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I printed the case in TPU, which stays flexible after printing. The flexibility lets the case make up for any feature that does not fit perfectly, makes the case much easier to put on and take off, and makes it more shock absorbent than rigid plastics like PLA. However, TPU makes the process less economical: it requires a slow print speed and lower nozzle and bed temperatures [3, 4], it is especially prone to stringing (which gets worse when more than one part is printed at a time), and prints often come off the plate unclean.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The aesthetic of the case is clean and simple. A textured build plate gives the back a bumpy finish, and the buttons, camera protector, and text insert were printed in dual-color PLA for an extra pop of color. Most of the back is covered by my wallet, so the rest of the design is a pattern of hearts. WHHFBK is a family motto, which makes this case personal to me and would limit its commercial success. On a small scale, the case could be sold with customizable text and cutouts, but for large-scale retail, FFF printing with these customizations would not be as profitable.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_bottom.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The case went through two prototypes before the final design. The first prototype fit my phone perfectly, held the camera protector securely, and kept the charging port, speaker holes, capacitive button, and MagSafe working. However, the button holes were not big enough to fit the inserts without pressing the phone's buttons, the camera cover did not fit over the curve of the camera bump and was not tall enough to protect the lenses, the MagSafe connection was weaker than ideal for my wallet, and the case had no design. For the second prototype, I increased the size and depth of the button holes, increased the taper on the camera cover and made it 2mm taller, decreased the back thickness, and added WHHFBK at the bottom of the case in a fun filament.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_camera_covers.jpg){: width="60%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; On the second prototype, the camera protector was functional and secure, the WHHFBK insert fit well, and the MagSafe wallet was held securely. The button holes were still not deep enough to hold the inserts without pressing the phone's buttons, and the case had only a minimal design. For the final version, I increased the wall size so the holes could be deeper, added supports for a clean print, created a second case with built-in buttons, and added the heart pattern from an SVG file.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/phone_prototypes.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The Fusion 360 model of the phone case is embedded below.

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b6028110b07d76ca583ad7a?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>{: width="90%" style="display: block; margin: 0 auto;"}

# Microfluidic Mold for Bacteria Testing

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; While volunteering in the Payne Lab, a biochemistry lab at Duke University, one of my projects was to improve the lab's ability to use microfluidic devices. Microfluidic devices are used to test how different materials and organisms interact. Their small size offers many benefits, but it also makes them difficult and costly to manufacture. 3D printing the molds for these devices can be a much more economical option.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_cad_angle.jpg){: width="50%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The design included many small side channels attached to a main channel. The side channels were designed to trap bacteria, allowing us to test how the bacteria respond to being immersed in different mediums. The channels are only 5 microns thick, which made 3D printing the mold challenging. I designed the model in Fusion 360 and printed it at Duke University.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_cad_channels.jpg){: width="30%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The design went through several iterations, including adding indicators for where to insert the supply tubes, adjusting the size and spacing of the side channels, and refining the ends where the tubes for adding and removing different mediums are inserted. The final mold can be easily cast and is more affordable and easier to use than commercial microfluidic devices.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/mold_printed.jpg){: width="40%" style="display: block; margin: 0 auto;"}

# Self-Flying Drone

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In my high school robotics class, my partner and I spent a semester building and programming a self-flying drone. Because of our class's limited budget, we purchased an inexpensive drone kit along with several sensors to track the drone's location.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/drone_ground.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A GPS module, mounted on a plate above the drone to prevent interference, tracked the drone's position, and a Navio2 flight controller guided it along a preplanned path. The drone could take off, fly the route, and land without any human input. Because of the project's short timeframe, many components were quickly attached to the drone. With more time, I would make the design more robust and improve its appearance.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/drone_flying.jpg){: width="30%" style="display: block; margin: 0 auto;"}

# Horse Jumps

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Horse jumps, like most horse equipment, are extremely expensive; a single jump can cost over $1,000. Instead of buying them, I designed and built my own. The jumps needed to adjust to a wide range of heights, be durable enough to be left outside for long periods of time, and be lightweight and easy to move.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/jump_pvc.jpg){: width="40%" style="display: block; margin: 0 auto;"}

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The jumps use square PVC for the body and a wood base. To build them, I measured and marked each drilling location and used a drill press to keep every hole straight. I then built a wood support to create a strong base for the PVC to slide over. I also built a shorter set that uses wooden posts instead of PVC.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/jump_wood.jpg){: width="40%" style="display: block; margin: 0 auto;"}

# Light Switch Locator Light

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Finding light switches in the dark can be challenging, so I created a small light that attaches to the back of a light switch cover and gives off just enough light to easily locate the switch.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; My first version was simply a resistor and an LED wired together and hot-glued onto the switch cover. I then designed a mini custom PCB with a surface-mount LED, a resistor, and a power connector and glued it onto the back of the cover. Moving to a custom PCB made the circuit smaller and cleaner than the hot-glued prototype.

![My Image](/EmilySimmons.github.io/assets/img/other_projects/switch_circuit.jpg){: width="30%" style="display: block; margin: 0 auto;"}
![My Image](/EmilySimmons.github.io/assets/img/other_projects/switch_glow.jpg){: width="30%" style="display: block; margin: 0 auto;"}

{% include gallery caption="Other Small Projects" %}

# Sources
1. Pew Research Center, "Mobile Fact Sheet," Nov. 13, 2024. https://www.pewresearch.org/internet/fact-sheet/mobile/
2. A. Kiersz, "REVEALED: Here's Who Uses iPhone Cases And Why," Business Insider, Jul. 8, 2014. https://www.businessinsider.com/iphone-case-survey-2014-7
3. Polymaker US, "PolyFlex TPU95 – Versatile, Flexible, and Printer-Friendly TPU." https://us.polymaker.com/products/polyflex-tpu95?variant=39574341681209
4. J. O'Connell, "The Best TPU Bed & Print Temperature Settings," All3DP, May 7, 2024. https://all3dp.com/2/best-tpu-print-temperature-bed-filament/
