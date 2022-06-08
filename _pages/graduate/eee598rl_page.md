---
title: "Reinforcement Learning in Real World Robotics Task Training with UR5"
layout: splash
permalink: /eee598rl_page/
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
- [About](/eee598rl_page/#about)<br>
- [Keywords](/eee598rl_page/#keywords)  <br> 
- [Abstract](/eee598rl_page/#abstract) <br>
- [TRPO Demonstration Low Reward](/eee598rl_page/#trpo-demonstration-low-reward)  <br>
- [TRPO Demonstration High Reward](/eee598rl_page/#trpo-demonstration-high-reward)  <br>
- [TRPO Demonstration Timelapse](/eee598rl_page/#trpo-demonstration-timelapse)  <br>
- [Final Presentation](/eee598rl_page/#final-presentation) <br>
- [Project Write Up](/eee598rl_page/#project-write-up) <br>
- [Return to Grad Projects](/grad_projects/) 


## About
Reinforcement Learning (RL) reduces the mathematical complexity of robotic tasks such as reaching by rewarding or penalizing a system through a series of training tasks. This project improves the reproducibility of an RL project revolving around real reaching tasks with a UR5 arm. Overall, two methods of RL were applied to the UR5: trust region policy optimization (TRPO) and proximal policy optimization (PPO). These then trained in real time on the UR5 hardware, successfully training the UR5 arm to reach specific points in a 2D space optimally. <br><br> 
For more in depth description and visualization refer to the [Final Presentation](/eee598rl_page/#final-presentation) and the [Project Write Up](/eee598rl_page/#project-write-up).
## Keywords
Reinforcement Learning, Python, UR5, Ubuntu, Virtual Machine, Github, Docker

## Abstract
Robotics are becoming increasingly usable in commercial and industrial settings to perform monotonous/repetitive
tasks. However, the controls architecture for a system developed for basic actuation and minimal environmental cognition feedback is very different than one that is aware of its environment and uses this intuition to base current and future decisions off of. As this trend continues, there is demand in the space for improvement of autonomy and robustness of these systems. Our team investigated the practical implementation of different Reinforcement Learning (RL) algorithms and approaches on an UR5 robotic manipulator. The team found that benchmarking different solutions provided a sense of practical implementation of our studies, and we believe this work also serves as a resource with tangible juxtaposition of different RL approaches; analytically explaining the pros and cons of optimal agent creation, training, and implementation.The team also evaluated the replication of some of the most state-of-the-art algorithms and development environments for real-world robotic implementation, that being SenseAct. As replication is one of the most difficult things to accomplish in this novel space, the successful implementation of our project supports the viability and usability of SenseAct as a launching platform for Reinforcement learning deployment on their supported robotic platforms.

## TRPO Demonstration Low Reward 
Initial RL with a very low reward (-69).
<iframe width="560" height="315" src="https://www.youtube.com/embed/ID5nXswgAEQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## TRPO Demonstration High Reward 
Near the end of the RL simulation with a high reward (+257).  
<iframe width="560" height="315" src="https://www.youtube.com/embed/wuRKRXLQcfE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## TRPO Demonstration Timelapse
Timelapse of the UR5 arm performing reaching tasks, reward of +257. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/MOPrrYCnyA8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Final Presentation
<object data="{{ site.url }}{{ site.baseurl }}/_pages/graduate/EEE598RL/Team6_Sindorf_Finalpresentation.pdf" width="1000" height="1000" type='application/pdf'></object>

## Project Write Up
<object data="{{ site.url }}{{ site.baseurl }}/_pages/graduate/EEE598RL/Team6_name_PC2.pdf" width="1000" height="1000" type='application/pdf'></object>

<br><br>
[Return to top](/eee598rl_page/#table-of-contents)
