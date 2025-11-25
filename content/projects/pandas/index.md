---
title: Autonomous Vehicle Mapping & Localization (ROS2 + LiDAR + Sensor Fusion)
date: 2025-02-26
links:
tags:
  - Northeastern University
  - HugoBlox
  - Markdown
---

Technologies: ROS2 (Nav2, TF2), LeGO-LOAM, VLP-16 LiDAR, IMU fusion, GPS, RViz2, Python/C++

My first project at Northeastern, part of the Robot Sensing and Navigation course, allowing me to truly understand the core principles of the class and its real world applications.

A full mapping and localization system for a ground robot/autonomous vehicle, focused on producing stable 3D maps and accurate real-time odometry:

•	Integrated VLP-16 LiDAR, IMU, and GPS into a ROS2 launch architecture using TF2-corrected frames.

•	Implemented LeGO-LOAM for feature extraction, edge/plane segmentation, and LOAM-style scan-to-map odometry.

•	Tuned ICP parameters, outlier rejection, and voxel filtering for outdoor campus environments.

•	Performed multiple live campus runs to evaluate drift, loop closure consistency, and map convergence.

•	Generated 3D point cloud maps suitable for downstream localization and autonomous navigation.
<!--more-->
