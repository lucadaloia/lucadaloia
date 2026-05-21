# Luca Daloia

[`View my Resume (PDF)`](./Resume_Luca_Daloia_2026.pdf)

### Electrical & Computer Engineering | NC State University
I am a dual-degree student focused on Embedded Systems and hardware-software integration. My experience ranges from schematic capture, designing custom multi-layer PCBs and C-based firmware to architecting Python and Django platforms for data analysis, visualization, and automation.

---

### Technical Skills

* **Languages:** Python (Django, Tkinter, SQLite), C, C++, MATLAB, LaTeX, HTML
* **Coding Tools & Version Control:** VS Code, Antigravity IDE, Git, GitHub, Code Composer Studio (CCS) IDE & Debugger, Arduino IDE
* **EDA/Simulation & Modeling:** KiCad and Altium Designer(schematic & PCB layout), MATLAB, LTspice
* **3D Design and Printing:** Autodesk Fusion 360
* **Hardware & Embedded:** Schematic and PCB Design (KiCad and Altium Designer), ESP32, MSP430, ADC (Analog t Digital Converter) and DAC (Digital to Analog Converter), HDL (Verilog)
* **Systems:** Embedded Systems, Control Systems, Logic Design
* **Software:** Git/GitHub, Spice Simulation, KiCad, Altium Designer, Wireshark traffic analyzer
* **Test, Measurement:** Analog Discovery 3 / WaveForms (logic analyzer, scope, generators), Oscilloscope, Digital Multimeter (DMM), Bench Power Supply, Wireshark Traffic Analyzer
* **Workshop & Prototyping:** Precision Soldering (Surface Mount Devices & Through-hole), Dremel, Drill Press
* **Communication Protocols:** UART (Universal Asynchronous Receiver/Transmitter), IP, TCP (Transmission Control Protocol), CAN (Controller Area Network)
* **Software & OS:** MS Windows and Kali Linux, MS Office (Outlook, OneNote, Teams, OneDrive, Word, PowerPoint, Excel - Pivot tables, macros, functions), Google Workspace (gmail, Meet, Docs, Sheet, Slides, Drive), Dropbox, Oracle VirtualBox
* **AI:** Thoughtful use of AI assistants and coding tools (e.g., Claude, Gemini, ChatGPT) in my engineering workflow—including good judgment about when outputs need verification and awareness of confidentiality practices.

---
### **Soft Skills**
* **[`More details`](soft-skills.md)**

---

### Projects & Experience

#### **Caterpillar Auger Alignment System - (Senior Design) - Fall 2025/Spring 2026**
* **The Challenge:** Engineering a high-precision alignment status indicator tool for industrial hydraulic augers.
* **The Solution:** Designed a custom multi-layer PCB integrating an **ESP32** and **IMU sensors**. Developed C-based firmware for real-time orientation feedback via ESP-NOW for wireless communication, and LEDs and buttons for user interface.
* **Role:** Hardware & UI Subsystem Lead:
    - **Hardware:** Designed and routed custom multi-layer PCBs for both the IMU and UI subsystems, transitioning the project from breadboard prototypes to a ruggedized industrial solution.
    - **Firmware:** Developed the C-based UI logic, including real-time alignment calculations, interrupt-driven button inputs, and LED control for operator feedback.
* **Tech:** KiCad, Altium Designer, C, ESP32, ESP-NOW, PCB Design, IMU Sensors
* **Skills Applied:** Prototype development, testing, validation, and refinement, hardware and software integration, C based firmware development, circuit validation (AD3, oscilloscope, and DMM), PCB design and fabrication, board bring-up, soldering, systems-level design, documentation and collaboration.
* **More Details:**
    - [`Project Page`](projects/auger-alignment-system/project_details.md)


#### **Custom PCB Design (ECE 492) - Spring 2026**
* **Description:** Engineered a microcontroller-based embedded system by interpreting manufacturer schematics to design a custom power circuit validated through Spice simulations. Using KiCad, I developed a multi-layer PCB integrating LDRs, LEDs, and tactile buttons while managing complex routing power planes, and mechanical constraints. Developed bare-metal C firmware to manage high-speed peripheral communication and real-time sensor data processing.
* **Tech:** C, MSP430, ADC/DAC, GPIO, KiCad, PCB Design, Datasheets, LTspice, Power Circuit Design
* **Skills Applied:** Power Circuit Design, PCB Layout and Routing (KiCad, multi-layer design), Firmware Development (C, MSP430), Component Selection (based on datasheets), Simulation (LTspice), Validation and Testing (multimeter).
* **More Details:**
    - [`Project Page`](projects/custom-pcb-design/project_details.md)
    - [`Project Repository`](https://github.com/lucadaloia/MSP430-LDR_ECE492)

#### **Autonomous IoT Robotic Platform (ECE 306) - Fall 2025**
* **Description:** Designed and implemented a bare-metal TI MSP430-based autonomous robotic car with integrated power regulation, H-bridge motor control, and multi-sensor fusion, and PID controller for precision navigation. Programmed the embedded system in C to process real-time ADC data from IR emitter-detector arrays, enabling the vehicle to detect and track physical course boundaries and transition between autonomous line-following and manual operation. Developed a full-stack IoT solution by integrating a Wi-Fi module and a web-based steering interface, while verifying all hardware subsystems using Analog Discovery and digital voltmeters to ensure signal integrity and power stability.
* **Tech:** C, MSP430FR2355, ESP32, IoT, Serial Communication, UART, ADC/DAC, GPIO, interrupts, timers, PID controller,  Analog Discovery 3, Debugging using Code Composer Studio IDE
* **More Details:**
    - [`Project Page`](projects/ece306-autonomous-iot-car/project_details.md)
    - [`Project Repository`](https://github.com/lucadaloia/MSP430-IoT_Car_ECE306)

#### **Research Assistant - Semiconductor Research Visualization Platform (for Prof. John Muth - NC State University) - Summer 2025**
* **The Challenge:** Organizing and comparing vast semiconductor device data sets for academic research.
* **The Solution:** Developed a Django-based application featuring interactive **Baliga’s Figure of Merit (BFOM) plots** to benchmark research results against global material limits.
* **Tech:** Python, Django, SQL, HTML, Git

#### **Sequential LED Turn Signals (ECE 212) - Spring 2025**
* **Description:** Developed a state machine–based circuit using a 555 timer, D flip-flops, and IC chips to implement sequential LED turn signals in a 1:24 scale Mustang model. Designed and optimized the system with Boolean simplification and K-Maps, integrating the final circuit into the car for a functional prototype.
* **Tech:** 555 timer, D flip-flops, XOR Gates, 4:1 Multiplexers, Boolean simplification, K-Maps
* **Skills Applied:** Digital logic design, circuit timing, state-to-output mapping, breadboard prototyping
* **More Details:**
    - [`Project Page`](projects/ece212-sequential-turn-signals/project_details.md)

#### **Internship - Extruder Performance Analysis Tool (Corning Inc.) - Summer 2024**
* **The Challenge:** Analyze extruder performance data from multiple Corning jacketing extruders across multiple cable plants to identify underperforming extruders and find possible causes.
* **The Solution:** Designed a Python-based tool to automate data extraction from the OSI PI Server and add it to a SQLite database. Developed a TkInter (pyhton) based GUI program to analyze and visualize the data, filtering the data to perform calculations and plot data for each zone of each extruder, allowing for easy comparison and identification of underperforming zones and extruders.
* **Role:** Division Controls Engineer Intern
* **Tech:** Python, Tkinter, SQLite, OSI PI Server, Data Extraction, Data Vizualization, Microsoft Excel, Automation, Data Analysis

#### **Internship - Conduit Selection Tool - Personal Project (Daloia Consulting) - Summer 2023**
* **The Challenge:** Performing manual NEC-compliant conduit fill calculations for complex cable schedules was time-consuming and prone to human error, risking potential non-compliance and project delays.
* **The Solution:** Engineered a Python-based automation tool with a TkInter GUI to standardize and accelerate the selection process. Developed a SQLite backend to manage cable specifications (type and diameter) and implemented logic to automatically calculate the minimum required conduit size based on user-selected cable quantities and National Electrical Code (NEC) regulations.
* **Tech:** Python, Tkinter, SQLite, NEC Regulations, Automation, Excel
* **More Details:**
    - [`Project Page`](projects/conduit-selection-tool/project_details.md)
    - [`Project Repository`](https://github.com/lucadaloia/conduit-selection-tool)

#### **Personal Project - CCTV Camera Fiel of View Excel tool - Summer 2021**
* **The Challenge:** Determining if security camera placements meet rigorous international standards for image quality was a manual, error-prone process that often led to sub-optimal surveillance coverage in high-stakes transit environments.
* **The Solution:** Created an MS Excel-based calculator that determines whether a camera's field of view (FOV) provides the necessary pixels on target to satisfy detection, observation, recognition, and identification requirements defined in the IEC EN62676-4 international standard.
* **Tech:** Microsoft Excel, IEC EN62676-4 Standards, Geometric Optics
* **Skills Applied:** Geometric and optical calculations, technical standard interpretation, feedback management, and tool development
* **More Details:**
    - [`Project Page`](projects/cctv-fov/project_details.md)
    - [`Project Repository`](https://github.com/lucadaloia/cctv-fov)

---

### Related Courses

- ECE 109 Introduction to Computer Systems
- ECE 200 Introduction to Signals, Circuits and Systems
- ECE 209 Computer Systems Programming
- ECE 211 Electric Circuits
- ECE 212 Fundamentals of Logic Design
- ECE 301 Linear Systems 
- ECE 302 Microelectronics
- ECE 306 Introduction to Embedded Systems: 
- ECE 308 Elements of Control Systems
- ECE 309 Data Structures and Object-Oriented Programming for Electrical and Computer Engineers
- ENG 331 Communication for Engineering and Technology
- ECE 407 Introduction to Computer Networking
- ECE 484/485 ECE Senior Design I/II 
- ECE 492 Special Topics in ECE - Introduction to Robotics & Autonomous Systems 
- ECE 492 Special Topics in ECE - Circuit Board Layout (Embedded Systems Hardware Design)
- PY 205 Physics for Engineers and Scientists I
- PY 206 Physics for Engineers and Scientists I Laboratory
- PY 208 Physics for Engineers and Scientists II
- PY 209 Physics for Engineers and Scientists II Laboratory

[`Course Details`](related-courses.md)

---

### Achievements
* **Dean's List:** 2022, 2024, 2025, 2026
* **Honors:** Invited to the NC State Honors Program
* **Best IoT Project Award in ECE Senior Design:** Caterpillar Auger Alignment System - Spring 2026
* **Best Team Work Award in ECE Senior Design:** Caterpillar Auger Alignment System - Spring 2026
  

**Connect with me:** 
* [`lfdaloia@ncsu.edu`](mailto:lfdaloia@ncsu.edu)
* [`LinkedIn`](https://www.linkedin.com/in/luca-daloia)
