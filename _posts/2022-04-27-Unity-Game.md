---
title: "Arduino controlled Unity Game"
layout: post
---

It's time for you to build your own game and joystick ofcourse. For this project, me and my friend built Unity Game that is controlled by joystick, MPU sensor, and Arduino. This game includes 3 different modes: free driving, collecting the coins and driving helicopter.


The communication between Arduino and computer is bidirectional, which means that Arduino sends data to computer as well as computer sends data to Arduino. Novelty that we want to achieve from this project is that we can achieve very simple and cheap implementations of virtual reality and augmented reality application once we successfully commicated Arduino, sensors with computer in both direction.

## Game Play:

In the behinning, player choose one of three options of the game: Free driving, Coin collecting, and Helicopter driving. If they choose the coin collection, they uses joystick to move around in the 3*3 led matrix. When they pushes the switch in the joystick, they determine the locations of the coins on the map with respect to map of leds. When they press on the red led, the communication is started and Arduino sends data to Unity using serial communication. The player tries to catch the coins in the map with driving car by joystick. When car collects the coins, the corresponding leds in the mapp turns off. If they choose the driving helicopter option, they use both MPU sensor and joystick. MPU sensor is used to determine the direction of the helicopter and joystick gives the movement. 

## Hardware:

- Arduino
- Adafruit BNO055 
- X-Y Joystick
- Leds
- Jumper Cables

We connected all the 9 leds to 2-10 digital pins on the arduino as output with a resistor for each. Digital 11-12 pin is connected to rgb led. Joystick data is connected to A0-A1 (for x-y values) and the switch on the joystick is connected to digital pin 13. Finally, 9-axis accelerometer data is connected to A4-A5. All necessary connections for GND and 5V are done for sensors and leds. 

## Software:

- You can find the Unity project from the following link: [Unity]()
- You can find the Arduino code from the following link: [Arduino](https://drive.google.com/file/d/1HiJcFdxNFYRmZIJlnGq5p45u66svs1Hc/view?usp=sharing)

## Videos:

<iframe width="560" height="315" src="https://www.youtube.com/embed/pQyqaxi_bWM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/pQyqaxi_bWM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



