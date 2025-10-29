---
title: "MBot - Autonomous Mobile Robot"
excerpt: "SLAM, Sensor Fusion, Particle Filter, PID<br/><img src='/images/mbot.png'>"
collection: portfolio
---

<center>
  <video width="560" height="315" controls>
    <source src="/images/mbot_vid.mp4" type="video/mp4">
  </video>
</center>

* Fabricated an autonomous robot completely from scratch, starting with interfacing different sensors and motors with Raspberry Pi, and then writing the controller for controlling these motors
* Wrote the complete SLAM algorithm in C++, including localization, mapping, and autonomous navigation
* Incorporated the path planning algorithm like A* to enhance the robot's path planning capabilities capabilities
* Solved the kidnapped robot problem by incorporating OpenCV's feature matching algorithm. This allowed to match the incomplete map with the complete map and then localize the robot
