---
layout: page
title: Localization Stack for a 4WD Drive Robot
description: Association - TIH Foundation for IoT & IoE, IIT Bombay
img: assets/img/torqy.jpg
importance: 1
category: work
---
<u>Application:</u> This project is being carried out in collaboration with the NRCG (National Research Centre for Grapes) to build an autonomous vehicle capable of doing under-canopy inspections in a grapes field.

It is divided in two parts - 

The objective of the first part was to demonstrate Nvidia Jetson Nano's on-board computing capabilities by running a SLAM algorithm and communicating with  RPI Pico W microcontroller over Wi-Fi.

<iframe width="560" height="315" src="https://www.youtube.com/embed/C1EqDBqLshw?si=zAjitVvAAzEA5cIf" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The second part focussed on upgrading the Localization stack by fusing sensor data from IMU, LiDAR, quadrature wheel encoders. 
    Since this is a ongoing project, my contributions have been in the following areas - 
    1. Establishing duplex communication between Nvidia Jetson Nano and RPI Pico W microcontroller over Wi-Fi. 
    2. Odometry calculation using IMU and wheel encoder sensors.

<div class="container-fluid p-0">
  <img class="img-responsive col-12" src="/assets/img/torqy_fc.jpg" alt="overview figure" />
  <h6 class="font-italic text-center" style="color: #78909c;">Figure 1:Overview of the system configuration.</h6>
</div>
