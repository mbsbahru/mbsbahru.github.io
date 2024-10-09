---
title: Object Detection and Communication for 9th International Roboboat Competition (2016)
---

*9th International Roboboat Competition - self-directed project at Barunastra Roboboat ITS.*

**Team:** Rudy D., Darwin S., Yohan P., *Muhammad Bahru Sholahuddin*, Ericza D. S., Anas M. N.

### My Responsibility:
Developed an Android-based object detection system using OpenCV, integrated with external sensors, and designed a communication pipeline between the Android application and a microcontroller via Bluetooth.

### Strategies:
- **Object Detection Pipeline:** Developed a comprehensive detection pipeline using color thresholding, noise reduction (Median and Gaussian filters), and morphological operations (Erosion and Dilation) to segment and refine object boundaries.
- **Object Classification:** Implemented algorithms to classify objects based on Hue-Saturation-Value (HSV) color space and geometric features such as form factor and number of edges, enabling the system to distinguish between various objects in the competition environment.
- **Performance Testing:** Tested the detection algorithm on recorded videos from the water field using a custom C++ program built with CMake to evaluate system performance.
- **Feature Extraction:** Created individual Java activities for each object type, extracting feature data such as hue, saturation, value, and shape parameters for real-time analysis within the application.
- **Camera Optimization:** Adjusted Android camera settings, including auto-focus, white balance, and exposure, to enhance detection performance under varying outdoor lighting conditions.
- **Sensor Data Integration:** Retrieved and processed raw sensor data from Android’s GPS, light sensor, accelerometer, gyroscope, and magnetometer for orientation data. Designed the system to allow easy resetting of orientation values, improving synchronization with object detection.
- **Microcontroller Communication:** Established communication with an STM32F4 microcontroller via UART over Bluetooth. Designed a custom parsing system to transmit real-time 2D object position data and sensor data (GPS, light, orientation) to the microcontroller for decision-making. Retrieved command data from the microcontroller to update the Android system with mission states.

### Links:
- [GitHub](https://github.com/MRoboSub/mrobosub/blob/devel/mrobosub_perception/src/hsv_pipeline.py)
- [Paper](https://robonation.org/app/uploads/sites/3/2019/10/ITSN_RB16_Paper.pdf)
- [Competition Rules and Tasks](https://drive.google.com/file/d/0BzV2g6noYWvrcllVVjJzWDJMbU0/view?usp=sharing&resourcekey=0-r_J7uLPxqzsBOr-YExZiJg)
- [Application](https://drive.google.com/file/d/19wvUKwV2xPmhx0Rs0UimR88snFOb-KrW/view?usp=sharing)

### Preview:
![Barunastra Nala Gab](../assets/img/project_barunastra.png)

