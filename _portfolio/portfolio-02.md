---
title: "Trajectory Tracking via MPC with Softening Constraints"
excerpt: "Differential Drive, MPC, Feedforward Control<br/><img src='/images/mpc_softening_constraints.png'>"
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
<img src="/images/mpc_softening_constraints.png" alt="" style="display: block; margin: 0 auto;">

* This was an implementation of the paper:"", to understand the concept of softening constraints.
* The feedforward control inputs are calculated from the reference trajectories (assuming the robot is already on the path) while the MPC controller ensures tracking of the reference signal
  * FF controller provides the baseline trajectory
  * MPC controller ensures tracking
* MPC controller incorporates soft constraints on the control signal and control increment
  * Guarantees convergence to a feasible solution for a QP
  * Allows for smooth trajectory tracking in presence of external disturbances

<img src="/images/mpc_softening_constraints.png" alt="" style="display: block; margin: 0 auto;">
