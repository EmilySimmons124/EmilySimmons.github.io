---
title: "Residential Lighting Control System"
excerpt: "A custom-built power electronics system for switching lights with a microcontroller/PLC for home automation"
header:
  image: /assets/img/lighting_banner.png
  teaser: /assets/img/Large-Format-3D-Printer-Thumbnail.png
gallery:
  - image_path: assets/img/Slide-3.png
  - image_path: assets/img/Slide-2.png
  - image_path: assets/img/Slide-4.png
   
---

# Features

* **Entire house automation capabilities.** Capable of switching 72 total lights, fans, floor heating, and appliances. High-voltage and high-current capabilities allow it to switch 120 or 240 volts and up to 25 amps.
* **High voltage and high current capabilities.** Able to switch up to 120 times a second. By utilizing pulse-width modulation in the lighting code, lights can be dimmed.
* **Easily installed, safe, and quiet.** The PCB is designed to be modular (more terminals can be added by adding another board) and compatible with DIN rail mounts. Additionally, the terminals have plug contacts for ease of wiring, and the components are finger-safe to prevent shocks. The PCB also has oversized heat sinks for thermal management, which eliminates the need for a fan. LEDs on the board indicate which lights are switched for ease of diagnostics and troubleshooting.
* **Over 10 million cycles.** A solid-state switch allows the lifespan of each light controller to exceed 10 million switching cycles.
* **Minimal power surges during switching.** A zero-crossing STR minimizes power surges when switching.
* **Custom PCB design for bulk fabrication.** Using a mask stencil and surface-mount solder, boards are easy and relatively inexpensive to produce.

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

{% include gallery caption="Large Format 3D Printer Gallery" %}
