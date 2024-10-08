---
title: Android Squirrel Image Detection and Alert using YOLO (2023)
---

*(CEE575 - Sensors, Data, Smart Systems) self-directed class final project at the University of Michigan.*

**Team:** Muhammad Bahru Sholahuddin and Stefano Sion Pizzi.

### My Responsibility:
Developed an Android application to detect the presence of squirrels, alert the user via a buzzer, update their position in a 2D frame using Google Sheets, and send their pictures.

### Strategies:
- **Dataset Collection:** Gathered 1,810 squirrel images and annotations from Google APIs to create a comprehensive dataset for training and testing.
- **YOLO Implementation:** Applied the You Only Look Once (YOLO) version 3 algorithm for training and testing the dataset using Google Colab, analyzing the optimal kernel size to balance detection accuracy and performance.
- **Android Application Development:** Created an Android application using the OpenCV library to process trained data. When a squirrel is detected, the app sends its position in the 2D frame via Bluetooth and emails the captured image to the user.
- **RedBoard Programming:** Programmed the SparkFun Photon RedBoard using the Particle Web IDE to receive data from the Android app through the HC-05 module using the Universal Asynchronous Receiver Transmitter (UART) protocol.
- **System Integration:** Developed a system where, upon squirrel detection, the RedBoard rings a buzzer and updates the squirrel's position in Google Sheets via the If This Then That (IFTTT) protocol.

### Links:
- [GitHub](https://github.com/mbsbahru/squirrel-detection-android)
- [Application](https://drive.google.com/file/d/1CiFBwprxuGFiuzDlLiYJxehNs_Sfk4YU/view?usp=sharing)
- [Video](https://drive.google.com/file/d/1zEdJWV1k0I3CAFBL1L8PJxqurIfKoDfc/view?usp=sharing)

### Preview:
![Squirrel Detection Android App](../assets/img/project_androidSquirrel_a.png)
![Squirrel Detection Android App](../assets/img/project_androidSquirrel_b.jpg)

