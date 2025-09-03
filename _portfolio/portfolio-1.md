---
title: "Model Predictive Control for Drone"
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

* Used the non linear dynamics to implement the non linear MPC. This non linear MPC uses non linear optimization tool in matlab that is fmincon. The initial input to this MPC is the initial position of the drone and the optimization task is to generate a control inputs which satisfy the constraints as well as the drone reaching the goal position.
* This non linear MPC runs until all the control inputs needed to reach the goal position are generated. We have a prediction horizon of 20 which means that after every optimization step, we will have 20 control inputs of which we take the 1st control input and apply it to the drone by forward simulating the drone dynamics using fourth-order runge-kutta method. On doing this we get the new state which is then fed back to the MPC as its initial state and this is performed until drone reaches the 
goal position.. 


<!-- <center>
  ![Trajectory of Drone](/images/obstacle_avoidance_traj.png)
</center> -->
<!-- <center>
    ![Trajectory of Drone](/images/obstacle_avoidance_traj.png)
</center> -->

<!-- <img src="/images/obstacle_avoidance_traj.png" alt="Trajectory of Drone" style="display: block; margin: 0 auto;"> -->


* In the cost function, we address the error in the state while simultaneously imposing penalties on high acceleration and input actions. This approach aims to mitigate excessively high acceleration maneuvers, which are impractical for the quad-copter’s capabilities. Conversely, we do not impose penalties on the quadcopter’s velocity, as our objective is to enable it to reach the goal state as quickly as possible. The parameters R, Q, and N were manually adjusted through a process of trial and error to achieve smooth performance.
