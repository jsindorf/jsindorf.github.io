---
title: "Skittle Sorting Device"
layout: splash
permalink: /skittle_page/
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
excerpt: "BME 210: Intermediate Engineering Design (Spring 2018)"

intro: 
  - excerpt: "some info here"   
   
---
## Table of Contents
- [About](/undergrad_projects/skittle/#about)<br>
- [Keywords](/undergrad_projects/skittle/#keywords)  <br> 
- [Description](/undergrad_projects/skittle/#description) <br>
- [Pictures](/undergrad_projects/skittle/#pictures)  <br>
- [Return to Undergrad Projects](/undergrad_projects/)  

## About
*Sort skittles by their respective color* was the only prompt and assistance this project started with. Through a Raspberry Pi, Python, Solidworks, a laser cutter, and a 3D printer, a final skittle sorting device was created. The final device was able to sort skittles with over 90% accuracy and performed at relatively fast speeds.

## Keywords
Raspberry Pi, Python, Solidworks, Laser Cutting, 3D Printing, Design

## Description
This project was my introduction to a real engineering design project. I had just learned the basics of Solidworks, Python, soldering, laser cutting, and 3D printing. Then the final project was 'simply' designing a device to sort skittles automatically. The final design can be found below in [pictures](#pictures). Originally a stepper-controlled carousel was used to rotate the sorting cups and drop skittles into, but was changed last minute to a servo-controlled slide to significantly improve speed. To sort the skittles, an RGB sensor was used and tuned to match each skittles color. The slide would then rotate to a specific cup to match the color of the skittle read by the RGB sensor. The design itself had a bowl with a sloped slotted carousel piece. This allowed skittles to be pushed into each slot to be read by the RGB. As this was controlled by a stepper motor, each slot was spaced by exactly one step of the motor. To put skittles into each slot a laser cut box with a light was used to make a controlled RGB reading environment. The box served as a wedge to push skittles until they fell into the slots. Once in the slot, the skittle could pass through the box and sit on the RGB sensor. Once a prediction is made, the stepper makes one step, the slide rotates, and the skittle is sorted.

## Pictures
<object data="{{ site.url }}{{ site.baseurl }}/_pages/undergrad/skittlesorter/sorterpics.pdf" width="1000" height="1000" type='application/pdf'></object>

