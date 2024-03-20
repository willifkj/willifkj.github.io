
---
title: "Microfluidic"
excerpt: "Mixing Device"
header:
  image: /assets/img/Pump Render 2.png
  teaser: /assets/img/Final_Mixing_Device.jpg
gallery:
  - image_path: /assets/img/Pump Render.png
  - image_path: /assets/img/Pump Render 2.png
  - image_path: /assets/img/Pump Wiring.png
  - image_path: /assets/img/Syringe-Pump.jpg
   
---

# Features

The purpose of the syringe pump device is to accurately control the movement of a syringe's plunger for dispensing and withdrawing liquids. Designed as a cost-effective alternative to commercial models, it utilizes a stepper motor, lead screw, and custom 3D printed parts. The device is suitable for both laboratory microfluidic applications and medical institutions for administering medicine and nutrients.

* **Accurate Liquid Control:** Precise movement of the syringe plunger for accurate dispensing and withdrawal of liquids.
* **Cost-Effective DIY Design:** A cost-effective alternative to commercial syringe pumps.
* **Modular Design:** Custom 3D printed parts, including syringe supports, motor mount, and electronics enclosure for easy assembly and disassembly.
* **Compatibility:** Accommodates syringes of sizes 5 mL to 20 mL.
* **Stepper Motor Mechanism:** Driven by a stepper motor coupled to a lead screw for controlled linear actuation.
* **Limit Switch:** Incorporates a limit switch to stop motion when the plunger reaches the end.
* **Adjustable Flow Rate:** Flow rate can be easily set and adjusted using the Arduino program.
* **LED Indicator:** LED changes color (green, yellow, red) to indicate operational status (running, paused, complete).
* **Clean Electrical Wiring:** Short, clean, and properly terminated electrical wiring with protection for soldered joints.
* **LCD Display:** Displays real-time flow rate and time remaining until the syringe pump is empty.
* **Potentiometer Control:** Flow rate can be controlled using a supplied potentiometer.
* **Protective Enclosure:** Electrical components and connections are protected from liquid exposure within the enclosure.
* **Unique Branding:** Incorporates unique branding, aligning with the team's name (Dimensional Divas).
* **Quiet Operation:** Acknowledges the noise limitation in healthcare settings.
* **Ease of Use:** Simple operation with an ON/OFF button and potentiometer for user-friendly experience.

# Part List

|           Off-the-shelf Parts          |   3D printed Parts   |
|:--------------------------------------:|:--------------------:|
|      Flanged Ball Bearing - F688ZZ     |   Button Gap Filler  |
| SunFounder IIC I2C TWI 1602 Serial LCD |       Carriage       |
|        Lead Screw - TR8x8x250mm        |   Cord Hole Filler   |
|                 LED 5mm                |        Coupler       |
|         Linear Rod - 8mmx200mm         |   Enclosure Drawer   |
|         Lock Collar Linear Rod         |    Enclosure Shell   |
|          Linear Bearing- LM8UU         |      End Support     |
|        Lock Collar Linear Screw        | Motor Mounting Plate |
|             Bolt - M3x10mm             |    Plunger Support   |
|       Thread Forming Screw - M3x8      |    Syringe Support   |
|              Tee Nut - M5              |                      |
|              Bolt - M5x8mm             |                      |
|             Motor - NEMA-17            |                      |
|              Nut - TR8x8-4             |                      |
|             Syringe - 5 & 20 mL        |                      |
|           V- Slot - 20x40x350          |                      |
|                  Knob                  |                      |
|           Push Button  9.5mm           |                      |

# Operation Instructions

* **Syringe Preparation:**
  * Fill the syringe with liquid.
  * Insert the syringe into the designated holders.

* **Power On:**
  * Ensure the ON/OFF button next to the LED light is in the OFF position.
  * Plug in the power cord. The LED turns yellow.

* **Flow Rate Adjustment:**
  * If a preset flow rate is desired, adjust the potentiometer to set the desired flow rate (0 to 100).
  * Press the ON/OFF button to start the device at the preset speed.

* **Alternate Flow Rate Adjustment:**
  * If potentiometer control is needed, start with the knob turned completely to the left or right (0 or 100 flow rate).
  * Press the ON/OFF button to start the device.
  * Adjust the knob to the desired flow rate.

* **Monitoring Operation:**
  * The LCD displays the current flow rate and the time countdown.
  * The LED turns green when the device is running, yellow when the flow rate is 0 with liquid remaining, and red when complete.

* **Power Off:**
  * Press the ON/OFF button to stop the device.
  * The LED turns yellow when paused.
  * Unplug the power cord.

Note: Follow safety guidelines, and ensure proper syringe placement for effective operation.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e1faab3ee761fd268?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Syringe Pump Gallery" %}

# Ardunio Code

The code is available here: [link](https://github.com/willifkj/Syringe-Pump/tree/main).
