---
title: "Model Predictive Control Based Path Following and Obstacle Avoidance for a Drone"
excerpt: "Explore my work in Model Predictive Control, guiding drones with advanced path following and obstacle avoidance capabilities<br/><img src='/images/drone_frame.png'>"
collection: portfolio
---
<!-- <video width="560" height="315" controls>
  <source src="/images/drone_vid.mp4" type="video/mp4">
</video> -->
<center>
  <video width="560" height="315" controls>
    <source src="/images/drone_vid.mp4" type="video/mp4">
  </video>
</center>

* I successfully defined and linearized the quadcopter’s dynamics, and evaluated its stability. 
* Further-more, implemented two distinct controllers - Linear Quadratic Regulator (LQR) and Model Predictive Control(MPC) - both of which demonstrated proficiency in trajectory  tracking. 


<!-- <center>
  ![Trajectory of Drone](/images/obstacle_avoidance_traj.png)
</center> -->
<!-- <center>
    ![Trajectory of Drone](/images/obstacle_avoidance_traj.png)
</center> -->

<img src="/images/obstacle_avoidance_traj.png" alt="Trajectory of Drone" style="display: block; margin: 0 auto;">


* Lastly, by adding constraints to the MPC and integrating the Rapidly-exploring Random Tree (RRT) algorithm to LQR, was able to create collision free paths and demonstrated the capability of the controllers to effectively avoid obstacles.
