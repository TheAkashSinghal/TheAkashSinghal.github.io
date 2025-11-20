---
layout: post
title: Discovery Project
description: The goal of this project was to design and produce a system that could turn the handle for the door in our dorm. The implementation plan of this project was to use a servo paired with specific hardware to provide a mechanical advantage to the system. <br> This was necessary as the door handle needed around 5 lbs of force to initiate the rotation, while the servo being used was only rated for 1.2 lb/ft of torque. To allow the system to provide the amount of force needed, I designed a pulley system. The pulley system utilised the measured distance the door handle needed to turn and applied that to the circumference of the pulley. Using this measurement and the length of the attached servo arm, I calculated the mechanical advantage from the system to be 5.6 lb/ft of torque. <br> When it comes to controlling the system, I experimented with a variety of devices. These include the Flipper Zero and a Raspberry Pi 5. This helped me to learn different methods for servo control, as the Flipper Zero and Raspberry Pi run different software. <br><br> The project came with more challenges  than anticipated - One of the main ones was wiring the servo to receive power and signal from different sources. In initial testing, I wired the power, ground, and control pin through the Flipper Zero. This allowed the servo to run, but didn't give it enough power to run with full torque. To get around this, I obtained a power source that could be plugged into the wall and provide 9 volts. Utilising a breadboard, I wired the servo's power and ground pins to the wall power source and the control pin to the flipper zero / Raspberry Pi. <br><br> <br><br> All in all, this project helped me to develop many skills and can be further improved on to make a useful solution to the problem of getting locked out. Through 
skills: 
  - Breadboarding
  - Servo Programming
  - CAD Process

main-image: /IMG_7716.jpg
---

# More Project Pictures

{% include image-gallery.html images="DP1.png, DP2.png, DP4.png" height="375" %}

