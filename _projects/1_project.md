---
layout: page
title: Localization Stack for a 4WD Drive Robot
description: Association - TIH Foundation for IoT & IoE, IIT Bombay
img: assets/video/tih_1_gif.gif
importance: 3
category: work
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .iframe-wrapper {
      text-align: center; /* Center the iframe within its container */
    }
  </style>
  <title>Centered Iframe</title>
</head>
<body>
  <div class="iframe-wrapper">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/C1EqDBqLshw?si=zAjitVvAAzEA5cIf" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>
</body>
</html>

<b style="font-size: 22px;">Application:</b> 
<p style="font-size: 18px; display: inline;">
    This project is being carried out in collaboration with the NRCG (National Research Centre for Grapes) to build an autonomous vehicle capable of doing under-canopy inspections in a grapes field.
</p>

<b style="font-size: 22px;">Description:</b> 

<ul style="font-size: 18px;">
  <li>The objective of the first part was to demonstrate Nvidia Jetson Nano's on-board computing capabilities by running a SLAM algorithm and communicating with the RPI Pico W microcontroller over Wi-Fi.</li>
  <li>The second part focussed on upgrading the Localization stack by fusing sensor data from IMU, LiDAR, quadrature wheel encoders. </li>
  <ul style="font-size: 18px;">
  <li>Establishing duplex communication between Nvidia Jetson Nano and RPI Pico W microcontroller over Wi-Fi.</li>
  <li>Odometry calculation using IMU and wheel encoder sensors.</li>
</ul>
</ul>

<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/torqy_fc.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/torqy.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <h6 class="font-italic text-center" style="color: #78909c;">Figure 1:Overview of the system configuration.</h6>
</div>