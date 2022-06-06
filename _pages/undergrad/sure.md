---
title: "Laser Cell Micropatterning Controller"
layout: wide
permalink: /sure_page/
author_profile: false
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
excerpt: "Clemson SURE program (Summer 2018)"

intro: 
  - excerpt: "some info here"   
   
---

## About
Laser patterning cells allows for a high spatial and temporal resolution. With the practice of laser guidance, cells (e.g., epithelial) can be patterned accurately to observe their behavior under a defined microenvironment. Eventually, laser patterned cells can be added to 3D bio-printed materials. In order to achieve this, a micron accurate stage that moves in XYZ directions, changes speeds, and stores and returns to specific 3D spatial positions is needed. This research is concentrated on development and design of the Joystick controlled stage.


## Keywords
Arduino, Solidworks, Laser Micropatterning, Bioengineering, Design, Circuits, Laser Cutting

## Description
This project was a summer research project through the Clemson SURE program. I was able to work with Dr. Gao and find a project based around laser micropatterning of cells. This is when a concentrated laser is used to pick up and moves cells, similar to an optical tweezer. By patterning cells in specific configurations, it is possible to observe or even force their interactions. This would be useful in custom 3D cellular molds, or even bio-printing. As it could be a method to add vascularity to 3D printed cell molds. <br>
This project itself focused on the control in 3D of a laser micropatterning stage to be used with an existing laser set up, and can be summarized in the [poster](#poster) below. A 3-axis translational stage was converted to take smaller step sizes with a 51:1 gear ratio of pulleys and timing belts. An Arduino was used as the main system control, and the control for the custom stage controller. The controller was laser cut out of acrylic based on Solidworks designed pieces. The controller itself was designed to assist in a laser micro patterning set up. It contained two Sparkfun joysticks to move the 3 axis stage stepper motors in x,y, and z. to control motor speed, two switches were added to slow down x,y and z respectively. This allows for more precise control and is necessary as fast movements could cause the laser to drop the cell. The other vital design feature are coordinate storage buttons. Four simple buttons were added to the controller to store and return to locations of interest. This design point is imperative to micropatterning as typically there is an inlet where all the cells are, and in a different location, there is the area in which cells are being placed. The buttons make it easy to return to these positions as it can be easy to get lost in a micro environment. Lasty, four LEDs are added to visually assist, showing power, x movement, y movement, and z movement.

## Poster
<object data="{{ site.url }}{{ site.baseurl }}/_pages/undergrad/sureprogram/Sure Poster_Sindorf.pdf" width="1000" height="1000" type='application/pdf'></object>

## Write-up
<object data="{{ site.url }}{{ site.baseurl }}/_pages/undergrad/sureprogram/SURE_paper_Sindorf.pdf" width="1000" height="1000" type='application/pdf'></object>

## [Back to Undergrad Projects](/undergrad_projects/)
