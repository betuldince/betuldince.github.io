---
title: "Digital Harp"
layout: post
image: /assets/image/sensors.PNG
---

Are you also suffering from the recently increased instrument prices? I have some good news for you. You can create your own instrument in your house and play it without even actually touching it.

Let me introduce you. Digital Harp.


You just need to buy some cheap sensors, cables and Arduino to build it from scratch. And we will use touchdesigner as software which is free for one year use. 

## Equipment:

- Arduino Uno or Mega
- Jumper Cables
- 6 Distance Sensors
- 1 Breadboard - 6 mini Breadboards
- 6 Lasers

## Software:

- Download Touchdesigner from the following link: [Touchdesigner](https://derivative.ca/download)
- Download following Touchdesigner file: [Touchdesigner File](https://drive.google.com/file/d/1In5s2i8YnAJlYcHDJ-aQ6-LN8U3ebDIz/view?usp=sharing)
- Download Arduino code from this link: [Drive](https://drive.google.com/file/d/1bU3dXInk-xQx-2WQWLa_MC2hVSN-eUcG/view?usp=sharing)

## How to

- Upload Arduino code to Arduino. 
- Connect trig and echo pins of the distance sensors as indicated in Arduino code. Set common ground and VCC line on Breadboard and connect them to Arduino, also connect each sensor's power and ground pins to these common lines. (Optinal) Then connect lasers to each sensor, by connecting "S" pin of laser to sensor's VCC pin and "-" pin of laser to ground of sensor. Put laser closer to the sensor to estimate where the sensor reading is. 
- Open Touchdesigner File

Your instrument is ready! Also you can change your instrument with downloading different audios and adding them to Touchdesigner.

## Fritzing Schematic 

![]({{page.image | relative_url}})


## Demo


<iframe width="560" height="315" src="https://www.youtube.com/embed/gESEOpzK2Sk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Update to Digital Harp

We made a box for the digital Harp project. And we set it up  for the exhibition to be opened in Abdülmecid Mansion in September.


 <iframe width="560" height="315" src="https://www.youtube.com/embed/_dfrmWjgpa8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

