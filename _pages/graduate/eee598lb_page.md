---
title: "Point Based Value Iteration (PBVI) and Partially Observable Markov Decision Process (POMDP) for Motion Artifact and Sensor System Energy Savings"
layout: splash
permalink: /eee598lb_page/
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
excerpt: "(EEE598 Fall 2021)"

intro: 
  - excerpt: "some info here"   
   
---

## Table of Contents
- [About](/eee598lb_page/#about)<br>
- [Keywords](/eee598lb_page/#keywords)  <br> 
- [Abstract](/eee598lb_page/#abstract) <br>
- [Problem Formulation](/eee598lb_page/#problem-formulation)  <br>
- [Project Write Up](/eee598lb_page/#project-write-up) <br>
- [Return to Grad Projects](/grad_projects/) 


## About
This work proposes a potential way to apply filters to reduce the motion artifacts of a photoplethysmogram (PPG) while also creating some sensor system energy savings. Through a Partial Observable Markov Decision Process (POMDP) framework and a Point Based Value Iteration (PBVI) algorithm, optimal actions can be selected to either observe accelerometer data for activity recognition, or choose to apply a noise reducing filter. This project is a theoretical approach and verifies that through the described methods, it would be possible to achieve energy savings and signal noise reduction while maintaining a high state prediction accuracy.<br> <br>
For more information about the project refer to the [Problem Formulation](/eee598lb_page/#problem-formulation). 

## Keywords
Matlab, Partially Observable Markov Decision Process (POMDP)/ Point Based Value Iteration (PBVI), Markov Chains

## Abstract
Commercially available sensors, such as the photoplethysmography (PPG), struggle with long term use due to energy constraint criteria. PPG sensors also provide accurate signal readings when the user performs little to no motion, including activities such as sitting, standing, or laying. Activities
with high motion such as walking or running receive noisy motion artifacts that potentially skew the data. This work proposes a way to apply filters to reduce the motion artifacts under high motion activities. Through a Partial Observable Markov Decision Process (POMDP) framework and a Point Based Value Iteration (PBVI) algorithm, optimal actions can be selected to either observe the accelerometer data for activity recognition, or choose to apply a filter. Simulations of states show promising results with overall positive reward of .04 when turning the accelerometer on and off. Keeping the accelerometer on at all times received a negative overall reward of -.26. These results indicate that the use of the filters and overall energy savings are possible, bringing up a way to allow the PPG sensor to be used in studies more representative of daily life.

## Problem Formulation
The problem formulation depicts the necessary setup and mathematics behind the project. It walks through the Markov chain, probabilities, PBVI set up and the POMDP. All of this allows for better understanding behind the complex Matlab algorithm that was written to solve the problem.
<object data="{{ site.url }}{{ site.baseurl }}/_pages/graduate/EEE598LB/Projectsetupformulation.pdf" width="1000" height="1000" type='application/pdf'></object>

<br><br>
[Return to top](/eee598lb_page/#table-of-contents)
