---
title: Android Touch HSV Color Picker (2014)
---

*Self-project during my role as a junior programmer at Barunastra Roboboat ITS.*

### My Responsibility:
Developed an interactive Android application to segment objects based on their Hue-Saturation-Value (HSV) color, allowing users to easily select and adjust HSV parameters through a touch interface.

### Strategies:
- **HSV Processing:** Implemented OpenCV for Android to process live camera frames and convert them into HSV color space for color-based object segmentation.
- **Dynamic HSV Adjustment:** Enabled users to adjust HSV range values dynamically via a touch interface, with real-time updates to filter and display objects based on the selected HSV values.
- **Real-Time Object Detection:** Detected and highlighted objects in real-time using color-based segmentation, displaying object features such as Hue, Saturation, and Value.
- **Interactive Control:** Developed interactive SeekBars for adjusting HSV thresholds, providing live feedback as users refined the segmentation settings.
- **Touch-Based HSV Selection:** Designed custom UI components allowing users to touch areas on the live camera feed and retrieve the HSV value of the selected point for calibration.
- **Contour Detection:** Utilized OpenCV’s contour detection to extract object boundaries and provide a visual overlay on detected objects within the camera feed.
- **Color Calibration:** Enabled manual color calibration through user selection and fine-tuning of HSV parameters, making the application suitable for vision-based robotic tasks like obstacle detection.

### Links:
- [GitHub](https://github.com/mbsbahru/android-hsv-pick)
- [Application](https://drive.google.com/file/d/1NhF9o5D2DPzwKQo5v9N8kOdDGCv6tQhN/view?usp=sharing)

### Preview:
![Android Color Picker](../assets/img/project_hsvPickerAndroid.jpeg)

