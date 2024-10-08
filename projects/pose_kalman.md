---
title: Pose Perfect - An Android Pose Estimation & Guidance App
layout: default
---

## Pose Perfect - An Android Pose Estimation & Guidance App (2024)

As part of the [ROB530 - Mobile Robotics](https://github.com/UMich-CURLY-teaching/UMich-ROB-530-public) self-directed class final project at the University of Michigan.

**Team:** Muhammad Bahru Sholahuddin, Mohammed Buhlaigah, Zih-En Tseng, Usman Shahzad.

### My Responsibility:
I developed an Android application to perform 3D linear and angular pose estimations (surge, sway, heave, roll, pitch, yaw) using a single-vision camera relative to the object's frame of reference. I also refined the estimations using the Android accelerometer and gyroscope sensors, applying a Kalman filter and integrating the team's filtering and control algorithms into the application.

### Strategies:
- Implemented HSV object segmentation, noise reduction (smoothing and morphological operations), and contour refinement (Convex Hull).
- Extracted object features (centroid, edges, vertices) and displayed their positions within the camera's 2D frame.
- Performed camera calibration to obtain intrinsic parameters such as the optical center, focal length, skew coefficient, and distortion coefficients of the Android camera.
- Applied the Perspective-n-Point (PnP) algorithm to compute the object’s translation vector and rotation matrix relative to the camera frame.
- Performed inverse frame transformation to use the object as the reference frame, obtaining the camera’s linear ($x$, $y$, $z$) and Euler angular positions ($\phi$, $\theta$, $\psi$).
- Processed Android accelerometer and gyroscope data for Kalman filtering.
- Integrated frequency-based filtering and bang-bang control algorithms into the Android project.
- Developed a feature to save and reset the desired 6 DoF position and orientation, along with motion guidance based on in-frame positions.

### Links:
- [GitHub (Pose Perfect Project)](https://github.com/mbsbahru/Pose_Perfect)
- [Poster](https://docs.google.com/presentation/d/1ZVLhKT2xRZvxd_b7FyPOwXysKnrry6pg24x-qFHhQ1k/edit?usp=sharing)
- [Paper](https://drive.google.com/file/d/1wzO3Bb32BaxBVvxDnijjk-b8pXrSOTyf/view?usp=sharing)
- [Android Application](https://drive.google.com/file/d/1H8T5yAWxWS_5-SAM8eWqe3GmNhLwfa4T/view?usp=sharing)

### Preview:
![ROB530 Project Screenshot 1](../assets/img/project_posePerfect_a.png)
![ROB530 Project Screenshot 2](../assets/img/project_posePerfect_b.png)

