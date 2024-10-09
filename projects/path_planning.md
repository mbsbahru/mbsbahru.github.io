---
title: Visual Path Planning for Underwater Manipulation (2024)
---

As part of the self-directed class final project for *ROB572 - Marine Robotics*, at the University of Michigan.

**Team:** Muhammad Bahru Sholahuddin, Kathryn Wakevainen.

### My Responsibility:
Developed a Python program for estimating the 3D linear and angular poses (surge, sway, heave, roll, pitch, yaw) of underwater objects relative to a camera frame of reference and vice versa. The application provided recorded or real-time visualization of the 6-Degree-of-Freedom (6-DoF) motion trajectory, displaying the camera's position and orientation. Additionally, the algorithm's performance was evaluated to ensure accuracy and reliability in pose estimations.

### Strategies:
- **Object Segmentation:** Applied HSV thresholding to segment two underwater objects based on color profiles. Refined segmentation with smoothing techniques, contour treatment, and color enhancements to improve detection accuracy in low-visibility underwater environments.
- **Feature Extraction and Tracking:** Developed an algorithm for real-time tracking of corner vertices, extracting key features such as vertex positions and edge lengths for geometric classification.
- **Camera Calibration:** Performed camera calibration using Matlab to estimate intrinsic parameters, including optical center, focal length, skew coefficient, and distortion coefficients, to correct lens distortions.
- **Pose Estimation:** Applied the Perspective-n-Point (PnP) algorithm, Rodrigues' rotation formula, and inverse transformations to compute the camera’s linear ($$x$$, $$y$$, $$z$$) and Euler angular positions ($$\phi$$, $$\theta$$, $$\psi$$) relative to the object’s frame.
- **Data Smoothing:** Implemented an online low-pass filter to smooth trajectory data, reducing noise and sudden fluctuations for more stable motion representation.
- **Accuracy Evaluation:** Calculated and displayed the reprojection error for each frame to assess pose estimation accuracy and provide insights for further improvement.
- **Visualization:** Visualized the 6-DoF motion trajectory of the camera relative to the object’s frame using Matplotlib, generating detailed plots showing the path and orientation of both the camera and objects.

### Links:
- [Paper & Code Attachment](https://drive.google.com/file/d/16MCcvLWL8GJQi-GOwGc-1yQGixkHIaVR/view?usp=sharing)
- [Video](https://drive.google.com/file/d/10Y9cqwjod6CYPV-1pDYdJVSm2V84LhuZ/view?usp=sharing)

### Preview:
![Visual Path Planning Demo](../assets/img/project_pathPlanning.png)
