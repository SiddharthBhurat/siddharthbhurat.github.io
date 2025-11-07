---
title: "Autonomous Robot Version 1"
excerpt: "Arduino Mega, GPS Sensor, IMU, Ultrasonic Sensor, Motor Driver<br/><img src='/images/auto_rob_v1.jpg'>"
collection: portfolio
---

<img src="/images/auto_rob_v1.jpg" alt="Autonomous Outdoor Robot" style="display: block; margin: 0 auto;">

* I started with this project to implement my idea of making a navigation stack which can be used for different purposes like autonomous deliveries, automation in agriculture and for use in defense during secret missions.
* It uses GPS sensor to get the local coordinates of the robot , magnetometer to determine the heading direction of the robot and accelerometer to know about its orientation.
* Once all this data is gathered by the sensors, the algorithm works on calculating the distance between the starting location coordinates of robot and destination coordinates defined by user. It also calculates the heading direction angle which the robot has to align with and start moving.
* The aim of this algorithm is to make the robot reduce distance between 2 coordinates while following the correct direction in a way to ensure that the robot reaches the destination.
* I have also equipped the robot with ultrasonic distance sensor to find distance to the obstacle and accordingly avoid them by taking appropriate turn. But on adding ultrasonic sensor to the same controller, the efficiency reduce, it was not able to perform well when the robot approached any obstacle. On identifying the reason for this, I found that the controller was not able to process everything at a faster rate.
* On encountering this problem, I started to build the next version of this robot which is based on Arduino micro-controller and  raspberry pi 4 with 8 gb ram which will increase the processing power as well as a provision to add a camera increasing perception efficiency of the robot.