---
layout: post
title: Ghost Detector
subtitle: Who you gonna call? Ghost detectors!
tags: [assignment, programming, arduino]
comments: true
---

## **When the sky turns to night and the a cool breeze whips by, be prepared to alert the masses of an oncoming ghost attack!**
This Arduino program uses sensory analog input in the form temperature and light in order to determine whether it is cold and dark enough for there to be a ghost nearby, wherein all of the red onboard LEDs will be turned on to alert others of the ghost detection.

**Tip/Trick for my Past Self:** Make sure the temperature and light thresholds are reasonable for the environment in which you are testing the code, otherwise you may test the program and falsely conclude that it works/doesn't work. It may be helpful to use the serial monitor to visualize what sensory input the Arduino is receiving and evaluate the subsequent output accordingly.

![ghostOff](https://amylam7.github.io/img/ghostOff.jpg)

**Figure 1.** The above image presents the working LED behavior from the Arduino code when the temperature input is not cold and the light input is not dark, indicating the absence of a ghost. The LED is off.

![ghostOn](https://amylam7.github.io/img/ghostOn.jpg)

**Figure 2.** The above image presents the working LED behavior from the Arduino code when the temperature input is cold and the light input is dark, indicating the presence of a ghost. The red onboard LEDs are turned on to warn others of the ghost detection. 
