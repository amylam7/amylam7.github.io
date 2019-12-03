---
layout: post
title: Scaredy Cat Sensor and Saver!
subtitle: Fear Death by Darkness No More with this Scaredy Cat Sensor and Saver!
tags: [assignment, programming, arduino, project]
comments: true
---
## **Wear your heart and your fears on your sleeve!**

Scared of the dark? Want everyone to sense your totally rational fear from miles away? Looking to stay prepared just in case your intense fear of the dark someday endangers your life? Look no further! With this stylish T-shirt, as the environment gets darker, the LED pulsing and heartbeat sounds will increase in frequency, mimicking the erratic racing of your heart when the sun goes down. If the darkness becomes so paralyzing that your heart literally stops and you enter cardic arrest, have a helpful bystander hold down the cute button in the center of your shirt to start playing the tune of "Stayin' Alive" by the Bee Gees to guide the process of hands-only CPR to keep the tempo of ~103 beats per minute-- the same tempo chest compressions should be given.

This project involved creating a simple circuit of LEDs in a heart shape and connecting a light sensor, buzzer, and button. The LEDs and buzzer served as analog outputs, while the switch was a digital input and the light sensor provided an analog input. The design uses a sine function to pulse the red LEDs in the heart shape in a manner similar to a heart-beat. Simultaneously, the buzzer plays heartbeat sounds similar to that of an EKG. Using the light sensor inputs, when the environment gets darker, the pulsing of the LEDs and the heartbeat sounds of the buzzer will increase in frequency, simulating the increasing heart rate of an individual who is scared of the dark. In addition, the homemade anatomical heart button in the center of the shirt can be pressed to play the song "Stayin' Alive" by the Bee Gees, which is a song commonly used to keep the beat of CPR compressions (~103 bpm), acting as an emergency button if the "Scaredy Cat" goes into cardiac arrest from such intense fear of the dark, a bystander can press their shirt to play the song to keep the rhythm of hand-only CPR until further help arrives.

## **Supplies List:**
+ 8 Red LEDs
+ 1 Lilypad Sparkfun USB Plug Main Board
+ 1 Lilypad Arduino Buzzer
+ 1 Lilypad Arduino Light Sensor
+ 1 Lilypad Arduino Switch
+ 5" x 5" Conductive Fabric
+ 6" x 10" Red Felt
+ Embroidery Floss (light blue, pink, purple)
+ Thread (white)
+ Conductive Thread
+ Needle
+ 1 M T-shirt

## **Paper Prototype**
![cs103 final proposal](https://amylam7.github.io/img/cs103 final proposal.png)

**Figure 1.** The image above presents the revised paper prototype and circuit design of my final project. I placed the switch by the buzzer to serve as a volume on/off switch so that the behavior of the project does not become too annoying by constantly beeping. I used felt to insulate the areas in the circuitry that appeared to overlap.

## **Aligator Clip Prototype**
![cs103 final paper prototype](https://amylam7.github.io/img/cs103 final paper prototype.jpg)

**Figure 2.** The image above presents the working aligator clip prototype of my project. Though there were not enough aligator clips available to attach all of the LEDs I planned to use (8 total), the aligator clip prototype of the simplified model appeared to work well. This was very helpful in visualizing and planning the circuit connections.

## **Final Product!**
![cs103 final bright](https://amylam7.github.io/img/cs103 final bright.jpg)

**Figure 3.** The image above presents the working behavior of the final product. In the bright environment, the LEDs are pulsing and the heartbeat is sounding at a relatively slow pace.

![cs103 final dark](https://amylam7.github.io/img/cs103 final dark.jpg)

**Figure 4.** The image above presents the working behavior of the final product. In the darker environment, the LEDs are pulsing and the heartbeat is sounding at a faster pace.

![cs103 final button](https://amylam7.github.io/img/cs103 final button.jpg)

**Figure 5.** The image above presents the working behavior of the final product. With the center heart button pressed, the LED pulsing halts and the tune of "Stayin' Alive" by the Bee Gees is playing. 

## **Tips to My Past Self:**
+ Try to coordinate increasing LED flashing and buzzer sounding frequency by using a common variable to change the pace of each.
+ Transcribing music to Arduino code can be difficult if you have no musical experience! Have a friend proficient in reading music handy. Know that pitches (sharps vs flats) can change the melody a lot! The toneMelody example code in Arduino can be very helpful, look at what they did and then apply to your desired tune.
+ Secure the components to the material before starting to sew (tape is great for this). Also, make sure that when you're laying out the components, to visualize the circuits corresponding to the paper prototype!
+ Be very very careful about insulating your circuits if you expect to have overlapping traces... this can mess up the entire behavior of the project and you will have to cut up parts to figure out what is overlapping. Insulating with felt/fabric is great because there is no waiting/drying time and it's not permanent!
+ Stretchy fabric is kind of tough to work with, don't tighten too much. Keep the stitched relatively loose.

## **Sources:**
+ https://github.com/nseidle/AxelF_DoorBell/wiki/How-to-convert-sheet-music-into-an-Arduino-Sketch
+ https://www.virtualsheetmusic.com/score/HL-402078.html
+ https://www.sparkfun.com/tutorials/329
+ https://learn.sparkfun.com/tutorials/ldk-experiment-4-make-your-own-button__hstc=250566617.52e89d2374fe2679f75991a214d3efab.1573705213617.1574126861707.1575241970301.4&__hssc=250566617.1.1575241970301&__hsfp=969430428
+ https://learn.sparkfun.com/tutorials/insulation-techniques-for-e-textiles/all
