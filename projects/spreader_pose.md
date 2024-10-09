---
title: Pose Detection Prototype of CC Spreader using Computer Vision (2017)
---

*Final Project at the Institut Teknologi Sepuluh Nopember.*

**Team:** Muhammad Bahru Sholahuddin, Juniarko Prananda, M.T. (Advisor), Dr. A. A. Masroeri (Advisor).

### My Responsibility:
Developed a computer vision-based system to detect the Container Crane (CC) spreader and estimate its 3D orientation. Designed and implemented algorithms for image segmentation, noise reduction, and feature extraction to identify the spreader's position and motion parameters.

### Strategies:
- **Lighting Condition Analysis:** Conducted experiments to analyze how changes in lighting conditions affect the accuracy of HSV-based color segmentation, developing an algorithm capable of handling varying outdoor illumination.
- **Image Segmentation:** Converted RGB images to HSV color space and applied adaptive thresholding to segment the spreader from the background. Implemented Median and Gaussian filters for noise reduction, followed by morphological operations (erosion, dilation) to remove small artifacts. Applied the Convex Hull algorithm for precise contour detection of the spreader.
- **Feature Extraction:** Identified the spreader's corner points and calculated geometric properties such as centroid, area, and orientation angles. These features were used to estimate the spreader's 3D pose (position and orientation) relative to the camera and to calculate motion parameters, including sway, skew, trim, and list rates.
- **System Simulation:** Integrated the algorithm into a simulated environment to evaluate its performance in detecting the spreader’s motion, comparing the results with ground-truth measurements to validate pose estimation accuracy.
- **Robustness Testing:** Tested the algorithm under different lighting and environmental conditions, assessing its robustness and fine-tuning the segmentation and feature extraction processes for improved detection accuracy. Proposed enhancements for real-time application, including advanced tracking algorithms and adaptation to varying weather conditions.

### Links:
- [Project Report & Code Attachment](https://core.ac.uk/download/pdf/291464546.pdf)
- [Journal](https://www.praiseworthyprize.org/jsm/index.php?journal=ireme&page=article&op=view&path[]=22983)

### Preview:
![Bachelor Thesis Preview](../assets/img/project_spreaderDetection.png)

