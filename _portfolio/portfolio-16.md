---
title: "Monocular Depth Estimation for autonomous navigation"
excerpt: "Raspberry-pi camera, supervised learning, Depth<br/><img src='/images/depth_est.png'>"
collection: portfolio
---

<center>
  <video width="560" height="315" controls>
    <source src="/images/depthestimation.mp4" type="video/mp4">
  </video>
</center>

* Integrated and implemented the algorithm to use a single camera with raspberry pi to estimate depth and ego-motion of the robot's surrounding in order to get the robot a clearer picture of its surrounding and use it for navigation.
* The video above demonstrates monocular depth estimation from the robot.
* In depth estimation, it determines the distance of different objects in front of the robot in form of a depth map which denotes nearer objects and its surrounding by yellow color and as the distance of objects from robot goes on increasing, the color representing depth also goes on changing gradually. 
* This information can be used by processing the depth maps and extracting information required for navigation.