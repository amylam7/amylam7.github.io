---
layout: post
title: Analog Array
subtitle: Hip Hip Horray for some Analog Arrays!
tags: [assignment, programming, arduino]
comments: true
---

## **Check out this Array of possibilities for lighting up our PWM LEDs!**
This program uses two separate arrays, one holding integer values and another holding boolean values, to randomly select a PWM pin every 1 second, either turning said selected PWM LED on to a random value if it was off, or turning said selected PWM LED off if it was already on.

![synchronoussimultaneous](https://amylam7.github.io/img/synchronoussimultaneous.jpg)

**Figure 1** The image above depicts the working LED behavior of the Arduino program, with random PWM pins being selected every 1 second, which wil either turn the pin on to a random value (if the LED was off) or turning the pin off (if the LED was on).
