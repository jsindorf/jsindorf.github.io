---
title: "Embedded Deep Learning Heart Rate Estimation Device Prototype"
layout: splash
permalink: /bmi598_page/
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
excerpt: "(BMI598 Spring 2022)"

intro: 
  - excerpt: "some info here"   
   
---

## Table of Contents
- [About](/bmi598_page/#about)<br>
- [Keywords](/bmi598_page/#keywords)  <br> 
- [Description](/bmi598_page/#description) <br>
- [Video Demonstration](/bmi598_page/#video-demonstration)  <br>
- [Descriptive Slideshow](/bmi598_page/#descriptive-slideshow) <br>
- [Return to Grad Projects](/grad_projects/) 

## About
This project showcases an embedded heart rate (HR) estimation device. Using machine learning and TensorFlow lite, a trained algorithm can be deployed to an Arduino Nano 33 BLE Sense to make heart rate predictions in real time based on a wearable photoplethysmogram (PPG) and tri axial accelerometer.

## Keywords
Embedded Machine Learning, Python, Arduino/C/C++, Sensor systems, Wearable Device

## Description
This project is currently a focus in my research and is being expanded on. From the demo [video](#video-demonstration) below, it can be seen that the system has some issues with accurate HR estimation. However, it shows promise compared to the spark fun sensor as it can still provide a prediction even with motion artifact. Extensive preprocessing of the accelerometer and PPG data was done both on the database used, [found here](https://archive.ics.uci.edu/ml/datasets/PPG-DaLiA), and the incoming sensor data. The [slideshow](#descriptive-slideshow) below displays the steps used to create the final project. Extensive work was done in Python (specifically in Jupiter/ google collab) to train a deep NN from scratch, and to convert the trained model to TensorFlow lite. Extensive Arduino code was written to read the TensorFlow lite model, read the sensor data, preprocess the sensor data, and provide a prediction. Future work on this project focus on getting an accurate HR reading, as well as allowing for the code to work with new PPG and accelerometer sensors. The code for this project will eventually be made public. 

## Video Demonstration
<iframe width="560" height="315" src="https://www.youtube.com/embed/IdMJLKb7cA8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Descriptive Slideshow
<object data="{{ site.url }}{{ site.baseurl }}/_pages/graduate/bmi598/BMI598_F3_sindorf.pdf" width="1000" height="1000" type='application/pdf'></object>

<br><br>
[Return to top](/bmi598_page/#table-of-contents)
