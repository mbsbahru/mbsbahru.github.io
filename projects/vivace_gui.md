---
title: Control Interface of the VIVACE Renewable Energy Converter (2023)
---

Summer Research Project at the Marine Renewable Energy Lab (MRELab).

**Team:** Muhammad Bahru Sholahuddin, Pratik Shiveshwar, and Prof. Michael M. Bernitsas (Advisor).

### My Responsibility:
Converted the existing Raspberry Pi GUI Python program, used for interfacing with VIVACE parameters, into a C++ application. Implemented the Lightweight Communications and Marshalling (LCM) library for inter-process communication and real-time data visualization.

### Strategies:
- **Emulation for Testing:** Emulated the Raspberry Pi OS using QEMU (Quick Emulator) CLI to test the program without needing lab hardware, enabling efficient development and testing cycles.
- **GUI Migration:** Migrated the Python-based GUI, originally built using `tkinter`, to C++ with the `gtkmm` library, improving performance and enhancing interface responsiveness.
- **LCM Integration:** Integrated the LCM library to enable communication between the GUI and sensor systems, such as encoders and programmable load controllers, facilitating real-time monitoring.
- **Real-Time Visualization:** Developed dynamic widgets, including gauges and sliders, to visualize critical parameters like generator voltage, current, encoder position, and velocity in real time.
- **Multi-Threading Architecture:** Implemented a multi-threaded architecture to handle concurrent data processing and GUI updates, improving responsiveness during high-frequency data transmission.
- **Application Testing:** Conducted thorough testing of the application in the emulated environment to identify and resolve potential issues before deploying the system on actual hardware.

### Links:
- [Project Code](https://drive.google.com/file/d/1mrszazPAsx-A8ybuW5P6sL-GKlr_77TC/view?usp=sharing)

### Preview:
![Control Interface of the VIVACE Renewable Energy Converter](../assets/img/project_vivaceGui.jpeg)

