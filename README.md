# Luca Daloia

[`View my Resume (PDF)`](./Resume_Luca_Daloia_2026.pdf)

### Electrical & Computer Engineering | NC State University
I am a dual-degree student focused on hardware-software integration. My experience ranges from designing custom multi-layer PCBs and C-based firmware to architecting Python and Django platforms for data analysis, visualization, and automation.

---

### Technical Skills

* **Languages:** Python (Django, Tkinter, SQLite), C, C++, MATLAB, LaTeX, HTML
* **Coding Tools & Version Control:** VS Code, Antigravity IDE, Git, GitHub, Code Composer Studio (CCS) IDE & Debugger
* **EDA/Simulation & Modeling:** KiCad and Altium Designer(schematic & PCB layout), MATLAB, LTspice
* **3D Design and Printing:** Autodesk Fusion 360
* **Hardware & Embedded:** Schematic and PCB Design (KiCad and Altium Designer), ESP32, MSP430, ADC/DAC, HDL (Verilog)
* **Systems:** Embedded Systems, Control Systems, Logic Design
* **Software:** Git/GitHub, Spice Simulation, KiCad, Altium Designer, Wireshark traffic analyzer
* **Test, Measurement:** Analog Discovery 3 / WaveForms (logic analyzer, scope, generators), Oscilloscope, Digital Multimeter (DMM), Bench Power Supply, Wireshark Traffic Analyzer
* **Workshop & Prototyping:** Precision Soldering (SMD & Through-hole), Dremel, Drill Press
* **Communication Protocols:** UART, IP, TCP
* **IDEs:** VS Code, Google Antigravity, Code Composer Studio, Arduino IDE
* **Software & OS:** MS Windows and Kali Linux, MS Office (Outlook, OneNote, Teams, OneDrive, Word, PowerPoint, Excel - Pivot tables, macros, functions), Google Workspace (gmail, Meet, Docs, Sheet, Slides, Drive), Dropbox, Oracle VirtualBox
* **AI:** Thoughtful use of AI assistants and coding tools (e.g., Claude, Gemini, ChatGPT) in my engineering workflow—including good judgment about when outputs need verification and awareness of confidentiality practices.

---

### Soft Skills

* **Emotional Intelligence:** High emotional intelligence used to navigate team dynamics and professional relationships effectively.
* **Communication:** Firm believer that communication is the key to success; strong communicator who conveys ideas effectively in both written and verbal formats.
* **Teamwork & Collaboration:** Believe good teamwork is essential and that everybody has something to contribute and also to learn, regardless of individual expertise. Collaborate effectively with teammates to achieve common goals.
* **Autonomy & Research:** Work very well in teams yet maintain the ability to work independently when required, including performing independent research, development, and making critical design decisions.
* **Cross-Functional Collaboration:** Work and collaborate effectively with colleagues, other organizations, and individuals at all levels to achieve shared objectives.
* **Discipline & Ownership:** Very disciplined with a strong sense of responsibility. Take full ownership of projects from inception to completion, often acting as the central coordinator who keeps progress on track.
* **Problem Solving:** Highly focused on solving problems; approach challenges from multiple angles and think "outside the box" to find creative solutions.
* **Analytical Skills:** Strong analytical skills used to evaluate complex technical requirements and data.
* **Learning Agility:** Capable of learning new topics and technologies quickly; adapt well to changing conditions and evolving project requirements.
* **Professionalism:** Maintain a professional and positive attitude; reliable, dedicated, and a hard worker committed to meeting technical goals on schedule.
* **Self-Motivation:** Highly self‑motivated to take direction and deliver quality work consistently.
* **Organization:** Organized and attentive to details, ensuring precision in both hardware assembly and firmware development.

---

### Projects & Experience

#### **Caterpillar Auger Alignment System - CAAS (Senior Design) - Fall 2025/Spring 2026**
* **The Challenge:** Engineering a high-precision alignment status indicator tool for industrial hydraulic augers.
* **The Solution:** Designed a custom multi-layer PCB integrating an **ESP32** and **IMU sensors**. Developed C-based firmware for real-time orientation feedback via ESP-NOW for wireless communication, and LEDs and buttons for user interface.
* **Role:** Hardware & UI Subsystem Lead:
    - **Hardware:** Designed and routed custom multi-layer PCBs for both the IMU and UI subsystems, transitioning the project from breadboard prototypes to a ruggedized industrial solution.
    - **Firmware:** Developed the C-based UI logic, including real-time alignment calculations, interrupt-driven button inputs, and LED control for operator feedback.
* **Tech:** KiCad, Altium Designer, C, ESP32, ESP-NOW, PCB Design, IMU Sensors
* **Skills Applied:** Prototype development and refinement, Hardware and software integration, C based firmware development, circuit validation (AD3, oscilloscope, and DMM)., PCB design and fabrication, soldering, systems-level design, documentation and collaboration.
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
* **Tech:** C, MSP430FR2355, ESP32, IoT, Serial Communication, UART, ADC/DAC, GPIO, interrupts, timers
* **More Details:**
    - [`Project Page`](projects/ece306-autonomous-iot-car/project_details.md)
    - [`Project Repository`](https://github.com/lucadaloia/MSP430-IoT_Car_ECE306)

#### **Research Assistant - Semiconductor Research Visualization Platform (for Prof. John Muth - NC State University) - Summer 2025**
* **The Challenge:** Organizing and comparing vast semiconductor device data sets for academic research.
* **The Solution:** Developed a Django-based application featuring interactive **Baliga’s Figure of Merit (BFOM) plots** to benchmark research results against global material limits.
* **Tech:** Python, Django, SQL, HTML, Git

#### **Sequential LED Turn Signals (ECE 212) - Spring 2025**
* **Description:** Developed a state machine–based circuit using a 555 timer, D flip-flops, and IC chips to implement sequential LED turn signals in a 1:24 scale Mustang model. Designed and optimized the system with Boolean simplification and K-Maps, integrating the final circuit into the car for a functional prototype.
* **Tech:** 555 timer, D flip-flops, IC chips, Boolean simplification, K-Maps

#### **Internship - Extruder Performance Analysis Tool (Corning Inc.) - Summer 2024**
* **The Challenge:** Analyze extruder performance data from multiple Corning jacketing extruders across multiple cable plants to identify underperforming extruders and find possible causes.
* **The Solution:** Designed a Python-based tool to automate data extraction from the OSI PI Server and add it to a SQLite database. Developed a TkInter (pyhton) based GUI program to analyze and visualize the data, filtering the data to perform calculations and plot data for each zone of each extruder, allowing for easy comparison and identification of underperforming zones and extruders.
* **Role:** Division Controls Engineer Intern
* **Tech:** Python, Tkinter, SQLite, OSI PI Server, Data Extraction, Data Vizualization, Microsoft Excel, Automation, Data Analysis

#### **Internship - Conduit Selection Tool - Personal Project (Daloia Consulting) - Summer 2023**
* **The Challenge:** Performing manual NEC-compliant conduit fill calculations for complex cable schedules was time-consuming and prone to human error, risking potential non-compliance and project delays.
* **The Solution:** Engineered a Python-based automation tool with a TkInter GUI to standardize and accelerate the selection process. Developed a SQLite backend to manage cable specifications (type and diameter) and implemented logic to automatically calculate the minimum required conduit size based on user-selected cable quantities and National Electrical Code (NEC) regulations.
* **Tech:** Python, Tkinter, SQLite, NEC Regulations, Automation, Excel

#### Personal Project - 
---

### Achievements
* **Dean's List:** 2022, 2024, 2025, 2026
* **Honors:** Invited to the NC State Honors Program
* **Best IoT Project Award in ECE Senior Design:** Spring 2026
* **Best Team Work Award in ECE Senior Design:** Spring 2026
  

**Connect with me:** 
* [lfdaloia@ncsu.edu](mailto:lfdaloia@ncsu.edu)
* [LinkedIn](https://www.linkedin.com/in/luca-daloia)
