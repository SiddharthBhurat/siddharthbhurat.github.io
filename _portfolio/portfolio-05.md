---
title: "Dynamic Path Planning with A Algorithm*"
excerpt: "A*, Dynamic Obstacle Avoidance"
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
<img src="/images/dynamic_path_planning.png" alt="" style="display: block; margin: 0 auto;">

* Developed a two-stage path planning system: global planning for initial route generation and adaptive re-planning for dynamic obstacle avoidance.
* Implemented a modified A* algorithm that evaluates paths using g-cost (distance from current position) and h-cost (heuristic distance to goal). Enhanced the standard algorithm by incorporating distance-based obstacle penalization rather than binary collision detection, creating a virtual inflation zone around obstacles to maintain safer clearance margins.
* The system executes planned paths incrementally, updating the robot's position after each segment. Upon environmental changes, the planner regenerates an optimal path from the new position to the goal, repeating this cycle until successful navigation. This approach balances computational efficiency with real-time adaptability to changing environments.
