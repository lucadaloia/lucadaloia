## **Caterpillar Auger Alignment System - CAAS (Senior Design) - Fall 2025/Spring 2026**

### **Project Overview**
The CAAS project was designed to solve a critical efficiency gap in agricultural operations: the precise alignment of augers for material transfer. I served as the Hardware & UI Subsystem Lead, taking the project from initial schematic capture to a field-validated prototype tested at the Caterpillar facility.

#### **My Technical Contributions**
- **Custom PCB Architecture:**Designed a multilayer KiCad PCB that integrated ESP32 microcontrollers with high-precision IMU (Inertia Measurement Unit) unit and custom LED interfaces for real-time angular feedback.
- **Firmware Engineering:** 
    - **Bare-Metal Architecture:** Developed a deterministic "super-loop" in C to manage system states, power regulation, and sensor polling.
    - **Sensor Data Processing:** Developed bare-metal C firmware to process IMU sensor data leaveraging the **i2cdevlib** (from [Jeff Rowberg](https://github.com/jrowberg/i2cdevlib)) and calculate precise Euler angles (Yaw, Pitch, Roll) to determine the auger's orientation relative to gravity.
    - **Real-Time Feedback Optimization:** Architected high-speed data handling logic to process inertial streams, ensuring the LED interface provided smooth, real-time visual feedback for precise field alignment.
    - **Wireless Communication:** Implemented **ESP-NOW** communication protocol to enable reliable, low-latency data transmission between the IMU subsystem and the UI subsystem, implmeenting two-way handshake for connection loss detection and band-switching in case of poor signal strength.



