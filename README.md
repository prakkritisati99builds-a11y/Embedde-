# Embedde-
This contains Embedde: Embedded Systems Projects

A collection of IoT and embedded electronics projects built with ESP32, sensors, and real-world applications. Each project demonstrates core embedded systems concepts: sensor integration, microcontroller programming, hardware design, and system optimization.

Projects
1. AC Buzzer Alarm

Smart Air Conditioner Electricity Wastage Alert System

Detects when an AC unit runs too long unattended and sounds an alarm. Uses temperature slope analysis to identify cooling cycles and a 20-minute timer to alert users.

Hardware: ESP32, DHT22 temperature sensor, slide switch, buzzer
Concepts: Temperature sensing, state machines, timers, pull-up/pull-down resistors
Skills: Sensor calibration, C code basics, datasheet reading
Status: ✓ Complete (Wokwi simulation + code)
2. Boiling Milk Alert

Temperature-Triggered Buzzer for Cooking

Monitors milk temperature and sounds an alert when it exceeds a user-adjustable threshold. Uses a slide potentiometer for real-time threshold adjustment and DS18B20 for high-temperature precision.

Hardware: ESP32, DS18B20 temperature sensor, slide potentiometer, buzzer, SD card module
Concepts: One-wire protocol, ADC analog input, SD card logging, direct temperature triggering
Skills: Protocol-level communication, analog-to-digital conversion, file I/O
Status: In progress (code done, SD logging pending)
3. Water Flow Sensor

Leak Detection System

Detects water flow and triggers an alert if water runs unattended. Useful for detecting leaks or monitoring water usage.

Hardware: ESP32, YF-S201 flow sensor, buzzer, PIR motion sensor
Concepts: Pulse counting, threshold detection, interrupt handling
Skills: ISR (interrupt service routines), pulse detection logic
Status: Planned
Repository Structure
Embedde/
├── README.md                      (this file)
├── ac-buzzer-alarm/
│   ├── README.md                  (project-specific docs)
│   ├── code/
│   │   ├── ac_buzzer.ino          (ESP32 sketch)
│   │   └── wokwi.json             (Wokwi simulation)
│   ├── docs/
│   │   ├── design_document.md     (technical design)
│   │   ├── BOM.md                 (bill of materials)
│   │   └── GPIO_pinout.md         (pin assignments)
│   └── images/
│       ├── circuit_diagram.png
│       └── working_demo.jpg
│
├── boiling-milk-alert/
│   ├── README.md
│   ├── code/
│   │   ├── boiling_milk.ino
│   │   └── wokwi.json
│   ├── docs/
│   │   ├── design_document.md
│   │   ├── BOM.md
│   │   └── GPIO_pinout.md
│   └── images/
│
├── water-flow-sensor/
│   ├── README.md
│   ├── code/
│   └── docs/
│
└── shared/
    ├── ESP32_GPIO_reference.md    (GPIO pin guide for all projects)
    └── sensor_datasheets/         (PDF datasheets)
Quick Start
Pick a project from the list above
Read the project's README (./project-name/README.md)
Check the BOM to gather components
Review the GPIO pinout to understand wiring
Simulate in Wokwi (if available) before building physical version
Follow the code and comments to understand the logic
Technologies & Tools
Microcontroller: ESP32 (WROOM-32)
Development: Arduino IDE / Wokwi (online simulator)
Languages: C/C++ (Arduino)
Sensors: DHT22, DS18B20, YF-S201, HC-SR501 (PIR)
Protocols: I2C, SPI, One-Wire, UART
Design: KiCad (for PCB layout, upcoming)
Learning Objectives

Each project reinforces core embedded systems skills:

Sensor Integration — reading analog/digital signals
Protocol Understanding — one-wire, SPI, I2C communication
Datasheet Reading — interpreting technical specifications
C Programming — setup/loop, GPIO control, timers, interrupts
Hardware Design — breadboarding, resistor selection, power management
PCB Design — translating breadboard prototypes to manufactured boards
Debugging — serial monitors, simulation, troubleshooting
Projects Progression
Beginner: AC Buzzer (temperature + boolean logic)
Intermediate: Boiling Milk (analog input + threshold detection + SD logging)
Advanced: Water Flow (interrupt handling + pulse counting)
Contributing

This repo documents learning projects. Feedback, improvements, and questions are welcome.

License

Open source. Feel free to build, modify, and learn from these projects.

Contact
GitHub: prakkritisati99builds
Project Timeline: July 2026 onwards
Next Stepsall the automation related Datasheets simulations and final outcomes of prakkriti-ROS-lab work 
