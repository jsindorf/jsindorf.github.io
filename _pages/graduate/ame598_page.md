---
title: "Anatomy Inspired Animatronic Head"
layout: splash
permalink: /ame598_page/
author_profile: true
toc: true
toc_sticky: true
#date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#333"
  overlay_filter: "linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5))"
  overlay_image: /cactus.jpg
  #actions:
  #  - label: "Download"
  #    url: "https://github.com/mmistakes/minimal-mistakes/"
  #caption: "none"
excerpt: "(AME598 Spring 2022)"

intro: 
  - excerpt: "some info here"   
   
---

## Table of Contents
- [About](/ame598_page/#about)<br>
- [Keywords](/ame598_page/#keywords)  <br> 
- [Description](/ame598_page/#description) <br>
- [Facial Expressions](/ame598_page/#facial-expressions)  <br>
- [Full Animatronic Head](/ame598_page/#full-animatronic-head) <br>
- [Return to Grad Projects](/grad_projects/) 

## About
Deriving from anatomical inspiration, this project creates a fully controllable animatronic head through an ESP32, stepper motors, and a Bluetooth connected PS3 controller. This project allows for individual control of both eyes, each end of the lips, and the neck in 3 dimensions. Through kinematic calculations, the PS3 controller can be mapped to control the neck through real time rotations of the controller.

## Keywords
ESP32, Arduino/C/C++, Solidworks, Kinematics, Bluetooth, Laser Cutting, 3D printing, Soldering

## Description
Expressive robotics tasked us with bringing life to our otherwise static engineering background. Through this course, I was able to take my cumulative knowledge that I have learned about robotics, and apply it to a creative yet technical final project. Initially an expressive face was made through a project tasked with 'facial expressions'. Using a 3D printed skull and a handful of ESP32 controlled stepper motors, we brought the face to life. With a Bluetooth connected PS3 controller, the eyes and lips were fully controllable allowing the user to make an endless amount of realistic, although creepy, facial expressions. The project was anatomy inspired such that the muscles on the face were all shaped and created to mimic real human facial muscles. A specific polyester fabric was laser cut to match the muscles natural stretch, or fiber direction. A full description behind the creation, coding, control, and demo are found in the facial expressions [video](#facial-expressions) below. <br><br>
To continue this project and expand the facial expressions, a neck was added to the system. Following the same anatomy inspiration, the neck muscles were laser cut to match. Control of the neck remains the most technical part of the project as it required kinematic calculation. Through end effectors and rotational matrices, it was finally possible to map the neck rotations to the built-in accelerometer in the PS3 controller. This unique control made the head mimic the movements done by the user making the range of expressions more intuitive to the user. A full video outlining the entire process, math derivation, and creation can be found in the full animatronic head [video](#full-animatronic-head) below. 


## Facial Expressions 
<iframe width="560" height="315" src="https://www.youtube.com/embed/X9lzpiYa7aQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
## Full Animatronic Head
<iframe width="560" height="315" src="https://www.youtube.com/embed/oKy2dadO6-c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br><br>
[Return to top](/ame598_page/#table-of-contents)
