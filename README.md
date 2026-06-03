<h1 align="center">👋 Hello, I'm Anandhu Krishnan R</h1>
<p align="center">
🚀 Embedded Systems Engineer • Robotics & Autonomous Systems • IoT • Firmware Developer <br>
📍 Kochi, India
</p>

---

## 🧠 About Me

I am an **Embedded Systems & Robotics Engineer** specializing in the design and development of intelligent, real-time autonomous systems. My work spans the entire stack, from low-level register configuration and RTOS task scheduling on microcontrollers to high-level multi-node system coordination using ROS 2 and web-based telemetry dashboards.

### 🔬 Core Competencies:
- **Autonomous Systems & Robotics**: ROS 2 node architecture (`rclpy`), distributed messaging, and WebSocket-based HMI dashboards (`rosbridge`, `roslibjs`).
- **Firmware & Real-Time Systems**: RTOS task management, semaphores, mutexes, and interrupt-driven peripheral control.
- **Hardware Protocols & Interfacing**: Direct register implementation of CAN, SPI, I2C, UART, and RS232.
- **IoT & Cloud Integration**: Real-time cloud streaming (Firebase), remote telemetry, and sensor network integration.
- **PCB Design & Prototyping**: Schematic capture, layout design, and hardware debugging.

---

## 🎯 Current Focus
- Developing deterministic multi-node robotic systems and testing sensor fusion frameworks.
- Optimizing low-latency data bridges between hardware transceivers (CAN/UART) and ROS 2 communication nodes.
- Designing high-availability IoT systems using ESP32 and cellular transceivers.

---

## 🔧 Tools, Tech & Platforms

- 💻 **Languages**: C, Embedded C, C++, Python, Shell Scripting
- ⚙️ **Robotics**: ROS 2 (Humble/Iron), `rosbridge_suite`, `roslibjs`, Node-to-Node Telemetry, Sensor Fusion
- 📟 **Microcontrollers / Processors**: STM32 (ARM Cortex-M), LPC2138 (ARM7), ESP32, PIC18F, ATmega32, Raspberry Pi
- 📡 **Protocols & Interfaces**: CAN Bus, FreeRTOS, SPI, I2C, UART, RS232, GSM (SIM800), GPS (NMEA)
- 🧰 **Tools**: MPLAB X, Keil uVision, STM32CubeIDE, Arduino IDE, Proteus, KiCAD, EAGLE, EasyEDA
- ☁️ **IoT/Cloud**: Firebase Realtime Database, Google Maps SDK, Blynk

---

## 💻 Tech Stack

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat&logo=gnu-bash&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00B5AD?style=flat&logo=freertos&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat&logo=espressif&logoColor=white)
![PIC](https://img.shields.io/badge/PIC-000000?style=flat&logo=Microchip&logoColor=white)
![ATmega](https://img.shields.io/badge/ATmega-000000?style=flat&logo=atmel&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat&logo=raspberry-pi&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![KiCAD](https://img.shields.io/badge/KiCAD-314CB6?style=flat&logo=kicad&logoColor=white)
![EAGLE](https://img.shields.io/badge/EAGLE-AE8B00?style=flat&logo=autodesk&logoColor=white)

---

## 🤖 Featured ROS 2 & Robotics Projects

| 💡 Project | 🔍 System Architecture & Description |
|---|---|
| 🔗 [ROS2_AGV_Core](https://github.com/Anandhu-AKR/ROS2_AGV_Core) | **Autonomous Smart Factory AGV System** coordinating 10 concurrent nodes (Sensors, BMS, Navigation, Safety) via custom publisher arrays. Includes a premium real-time glassmorphic control dashboard using `rosbridge_websocket` for live telemetry monitoring and emergency E-Stop capability. |
| 🔗 [ROS2_Drone_Core](https://github.com/Anandhu-AKR/ROS2_Drone_Core) | **Autonomous UAV Delivery System** utilizing 10 modular flight, telemetry, and failsafe nodes. Features structured GPS coordinates tracking, altitude stabilization, and a futuristic cockpit web interface showcasing live aircraft orientation and control. |
| 🔗 [ROS2_Fusion_System](https://github.com/Anandhu-AKR/ROS2_Fusion_System) | **Real-Time Sensor Fusion Hub** aggregating telemetry streams from simulated IMU and LiDAR sensors. Implements a central evaluation node that fuses orientation and distance data to broadcast workspace safety levels. |
| 🔗 [ROS2_Collision_System](https://github.com/Anandhu-AKR/ROS2_Collision_System) | **Active Safety System** utilizing a radar sensor simulator node and a guard evaluation node. Evaluates distance threshold parameters in real time to trigger warnings. |
| 🔗 [ROS2_Telemetry_System](https://github.com/Anandhu-AKR/ROS2_Telemetry_System) | **Kinematic Telemetry Translator** demonstrating node-to-node communication. Converts raw rotational wheel encoder pulses (RPM) to linear speed outputs based on standard kinematic models. |

---

## 🔌 Featured Embedded Systems & IoT Projects

| 💡 Project | 🔍 Hardware Description |
|---|---|
| 🔗 [PIC-PIC CAN Bus Data Bridge](https://github.com/Anandhu-AKR/PIC-PIC_CAN_Bus_Data_Bridge) | Inter-MCU communication bridge establishing reliable serial terminal message streaming between two PIC18F4580 controllers via a physical CAN network. |
| 🔗 [LPC2138-FreeRTOS-Semaphore-Mutex-Demo](https://github.com/Anandhu-AKR/LPC2138-FreeRTOS-Semaphore-Mutex-Demo) | Multitasking firmware demonstration using FreeRTOS counting semaphores and mutexes to manage resource sharing and task execution on an ARM7 (LPC2138) MCU. |
| 🔗 [GPS-Data-Parser-Arduino](https://github.com/Anandhu-AKR/GPS-Data-Parser-Arduino) | GPS localization project parsing raw NMEA-0183 sentences, extracting spatial coordinates, and converting UTC to IST for display. |
| 🔗 [FIREBASE_DHT11](https://github.com/Anandhu-AKR/FIREBASE_DHT11) | ESP8266 IoT logger mapping sensor parameters to a cloud database, showcasing real-time data streaming over Wi-Fi. |
| 🔗 [Automatic Door System PIR Arduino](https://github.com/Anandhu-AKR/Automatic-Door-System-PIR-Arduino) | Interrupt-driven control system parsing PIR motion events to actuate a servo-controlled entry gate with real-time status output. |
| 🔗 [PIC Microcontroller Projects](https://github.com/Anandhu-AKR/PIC_Microcontroller_Projects) | Curated repository containing firmware utilities, peripheral interfaces (ADCs, timers), and driver files written for the PIC18 microcontroller family. |
| 🔗 [AVR Microcontroller Projects](https://github.com/Anandhu-AKR/AVR_Microcontroller_Projects) | Register-level programming utilities, peripheral drivers, and applications written for ATmega microcontrollers. |

---

## 📫 Connect with Me

- 🌐 LinkedIn: [linkedin.com/in/anandhukr9394](https://www.linkedin.com/in/anandhukr9394)
- 📧 Email: akr9394@gmail.com

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Anandhu-AKR&theme=radical&hide_border=false&include_all_commits=true&count_private=true)
![](https://github-readme-streak-stats.herokuapp.com/?user=Anandhu-AKR&theme=radical&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Anandhu-AKR&theme=radical&hide_border=false&layout=compact)

---

## 🏆 GitHub Trophies

![](https://github-profile-trophy.vercel.app/?username=Anandhu-AKR&theme=radical&no-frame=false&no-bg=false&margin-w=4)

---

## ✍️ Random Dev Quote

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
> “When hardware meets logic, innovation happens.”  
> – AKR
