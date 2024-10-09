---
title: DC Motor Speed Control using Model Reference Adaptive Control (2022)
---

*(NA583 - Adaptive Control) self-directed class final project at the University of Michigan.*

**Team:** Max Wu, Nick Boston, *Muhammad Bahru Sholahuddin*.

### My Responsibility:
Derived the mathematical model of the DC motor and designed a Model Reference Adaptive Control (MRAC) system in Simulink.

### Strategies:
- **Mathematical Modeling:** Derived the mathematical model of the DC motor by applying Kirchhoff's Voltage Law to the electrical circuit and Newton's second law to the mechanical system. This resulted in a transfer function that represents the relationship between input voltage and angular velocity, characterized as a second-order system with parameters including torque constant ($$K_t$$), armature inductance ($$L$$), armature resistance ($$R$$), shaft moment of inertia ($$J$$), viscous friction coefficient ($$\beta$$), and back EMF constant ($$K_b$$).
- **MRAC System Design:** Designed the Model Reference Adaptive Control (MRAC) system using the direct Lyapunov method, ensuring system stability through the Strictly Positive Real (SPR) condition. The reference model was implemented as a second-order system to match the desired performance characteristics of the DC motor.
- **Adaptive Control Implementation:** Implemented the adaptive control law in Simulink, enabling continuous adjustment of control gains to minimize the error between the actual motor speed and the desired reference model response. The adaptation mechanism was designed to handle uncertainties in motor parameters and external perturbations.
- **System Testing and Simulation:** Simulated various operating conditions in Simulink to test the robustness of the MRAC system, analyzing performance under different scenarios.

### Links:
- [Project Report](https://drive.google.com/file/d/1EqPa1PUWieJr8wyfv5K7RIT7E4n0ZPSb/view?usp=sharing)

### Preview:
![Simulink DC Motor Model](../assets/img/project_dcMotorMrac_a.png)
![MRAC Subsystem in Simulink](../assets/img/project_dcMotorMrac_b.png)

