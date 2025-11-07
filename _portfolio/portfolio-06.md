---
title: "iLQR: Swing-Up of Double Inverted Pendulum"
excerpt: "LQR, Pendulum, Dynamics<br/><img src='/images/double_inv_pendulum.png'>"
collection: portfolio
---

<!-- <video width="560" height="315" controls>
  <source src="/images/drone_vid.mp4" type="video/mp4">
</video> -->
<!-- <center>
  <video width="560" height="315" controls>
    <source src="/images/drone_vid.mp4" type="video/mp4">
  </video>
</center> -->
<img src="/images/double_inv_pendulum.png" alt="" style="display: block; margin: 0 auto;">

* The double inverted pendulum is a challenging control problem due to its nonlinear dynamics and unstable equilibrium points. In this project, an application of iterative linear quadratic regulator (iLQR) to the swing-up task of a double inverted pendulum system. 
* The swing-up task involves raising the pendulum from a stable hanging position to an upright position and then maintaining it there. This is a challenging control problem due to the highly nonlinear and underactuated nature of the system. However, iLQR is a powerful optimization-based control method that can handle such complex systems. The approach involves iteratively solving a sequence of linear quadratic optimal control problems to find a near-optimal control policy for the pendulum system.
* The effectiveness of this approach was tested through simulation experiments, and show that iLQR can successfully swing up and balance the double inverted pendulum.
* Technical details can be found [here](https://drive.google.com/file/d/1-j8sqFAa0B6GxLWss21eYxrdsCY-Jwvh/view?usp=sharing)
