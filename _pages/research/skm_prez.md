---
title: "SKM 2023 Presentations"
layout: splash
permalink: /skm_page/
author_profile: true
toc: true
toc_sticky: true
#date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#333"
  overlay_filter: "linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5))"
  overlay_image: /asu_photo1.JPG
  #actions:
  #  - label: "Download"
  #    url: "https://github.com/mmistakes/minimal-mistakes/"
  #caption: "none"
excerpt: "(SKM23)"

intro: 
  - excerpt: "some info here"   
   
---

## Embedded Machine Learning for Heart Rate Estimation with Arduino
This work describes the use of Edge Impulse for embedded machine learning on an Arduino Nano 33 BLE Sense and a maxref PPG sensor. Includes end-to-end steps from device design, model building (spectrogram features, CNN), model deployment, and system validation testing on simple activities (sitting, standing, walking). 
<object data="{{ site.url }}{{ site.baseurl }}/_pages/research/files/SKM_2023_embed.pdf" width="1000" height="1000" type='application/pdf'></object>
## Day-to-day Heart Rate Estimation with PPG for Embedded Sensor Systems
This work expands upon the two fundamental heart rate estimation equations for use in an embedded, wearable device. The main goal is to reduce noise stemming from motion artifacts. Thus, two equations are used, one based on autocorrelation and the other on the fast frequency transform. A final sliding window is applied to make the equations more robust to noise. These methods were tested both on simulated PPG (neurokit2), and real data collected from a maxref PPG sensor. All analysis was performed in Matlab. 
<object data="{{ site.url }}{{ site.baseurl }}/_pages/research/files/SKM_2023_day2day.pdf" width="1000" height="1000" type='application/pdf'></object>
