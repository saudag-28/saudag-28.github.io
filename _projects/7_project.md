---
layout: page
title: Autonomous Visual Target Tracking
description: Association - Carnegie Mellon University
img: assets/video/autonomy.gif
importance: 2
category: academics
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
    <iframe width="560" height="315" src="https://www.youtube.com/watch?v=3ca_qIJWBGM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </div>
</body>
</html>

<p>
</p>

<b style="font-size: 22px;">Motivation:</b> 
<p style="font-size: 18px; display: inline; margin-bottom: 20px;">
Demonstration of enhanced tracking capabilities of dexterous manipulators using visuo-motor control.
</p>

<p>
</p>

<b style="font-size: 22px;">Application:</b> 
<p style="font-size: 18px; display: inline;">
The main objective of this project was to develop a system that allows a robotic manipulator to interact with dynamically changing environments. The primary functionality involves detecting, tracking, and engaging with randomly moving objects displayed on a screen. The system efficiently follows each object and handle them in sequence, showcasing the manipulator's precision and adaptability.
</p>

<p>
</p>

<b style="font-size: 22px;">Approach:</b>
<div class="col p-0">

    <a class="badge green waves-effect font-weight-light mr-1" href="/assets/pdf/16_662_Report_1A.pdf" target="_blank">PROJECT REPORT</a>

</div>
<ul style="font-size: 18px;">
  <li>Use Aruco markers for targets on a large display</li>
  <li>Track the markers by Visual Servoing using a Robot EF-fixed camera </li>
  <li>Verify tracking performance/register hit using a spotter system </li>
  <li>Spotter system: a independent vision-based hit validation system </li>
</ul>

<div class="container-fluid p-0">
  <img class="img-responsive col-12" src="/assets/img/autonomy.png" alt="overview figure" />
  <h6 class="font-italic text-center" style="color: #78909c;">Figure 1:System Architecture.</h6>
</div>