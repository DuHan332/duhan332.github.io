---
title: "Robot Arm Control using ROS"
collection: projects
type: "C++ Project"
permalink: /projects/project7
---

A projects that use ROS with C++ to control the robot arm.

Description
------

* Both kinematics and dynamic controlling are supported.

* Different functions are separated into different packages and handled by nodes, which make it easy to use them by ROS actions.

* ROS action could be used to integrate different actions together. For example, give several destinations are let the arm to move to them one by one.

* Read urdf and yaml files with information of robot arm to plan movements, which means it could used on different arms.

* Could test it by simulation without causing risks on actual robot arms.

Example
------

An arm (on simulation) that is cleaning cubes on the table.

<video width="480" height="272" controls>
  <source src="/images/clean.mp4" type="video/mp4">
</video>
