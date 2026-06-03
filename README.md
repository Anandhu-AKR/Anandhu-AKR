<h1 align="center">👋 Hello, I'm Anandhu Krishnan R</h1>
<p align="center">
🔌 Embedded Systems & Firmware Engineer • IoT Developer • Real-Time Systems • ROS 2 <br>
📍 Kochi, India
</p>

---

## 🧠 About Me

I am a hands-on **Embedded Systems & Firmware Engineer** specializing in bare-metal and RTOS-based firmware development, hardware-level communication protocols, and microcontroller peripheral interfacing. I build low-latency, deterministic applications on 8-bit, 16-bit, and 32-bit silicon architectures, and integrate them with IoT cloud infrastructure and ROS 2 middleware for robotic applications.

### 🔬 Core Competencies:
- **Firmware & Real-Time Operating Systems**: Task coordination, counting/binary semaphores, mutexes, and priority-based scheduling using FreeRTOS.
- **Hardware Protocols & Interfaces**: Low-level driver implementation of CAN Bus, SPI, I2C, UART, RS232, and serial bridging.
- **Microcontroller Peripherals**: Register-level configuration of Timers, Interrupts (ISR), ADC, PWM, and GPIO on ARM Cortex, PIC18, LPC2138, and ATmega architectures.
- **IoT & Wireless Telemetry**: Cloud data logging (Firebase), cellular/RF communication (GSM SIM800, ZigBee), and WiFi-enabled microcontrollers.
- **Robotics & Middleware (ROS 2)**: Interfacing physical/simulated firmware drivers with ROS 2 nodes (`rclpy`) and real-time WebSocket dashboard HMIs.

---

## 🎯 Current Focus
- Developing register-level firmware drivers for ARM Cortex-M microcontrollers.
- Interfacing hardware-level telemetry buses (like CAN and serial) with higher-level ROS 2 autonomous systems.
- Optimizing power management and low-latency task scheduling in FreeRTOS environments.

---

## 🔧 Tools, Tech & Platforms

- 💻 **Languages**: C, Embedded C, C++, Python, Shell Scripting
- ⚙️ **Microcontrollers / Processors**: STM32 (ARM Cortex-M), LPC2138 (ARM7), ESP32, PIC18F, ATmega32, NODEMCU, Raspberry Pi
- 📡 **Protocols, OS & Middleware**: FreeRTOS, CAN Bus, SPI, I2C, UART, RS232, GSM (SIM800), GPS (NMEA), ROS 2 (Humble)
- 🧰 **Tools & IDEs**: MPLAB X, Keil uVision, STM32CubeIDE, Arduino IDE, Proteus, KiCAD, EAGLE, EasyEDA
- ☁️ **IoT & Databases**: Firebase Realtime Database, Blynk, Google Maps SDK

---

## 💻 Tech Stack

![Embedded C](https://img.shields.io/badge/Embedded%20C-00599C?style=flat&logo=c&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00B5AD?style=flat&logo=freertos&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![PIC](https://img.shields.io/badge/PIC-000000?style=flat&logo=Microchip&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat&logo=espressif&logoColor=white)
![ATmega](https://img.shields.io/badge/ATmega-000000?style=flat&logo=atmel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![KiCAD](https://img.shields.io/badge/KiCAD-314CB6?style=flat&logo=kicad&logoColor=white)
![EAGLE](https://img.shields.io/badge/EAGLE-AE8B00?style=flat&logo=autodesk&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

---

## 🔌 Highlighted Embedded Systems & IoT Projects

| 💡 Project | 🔍 System Architecture & Firmware Details |
|---|---|
| 🔗 [PIC-PIC CAN Bus Data Bridge](https://github.com/Anandhu-AKR/PIC-PIC_CAN_Bus_Data_Bridge) | **Inter-MCU Communication Protocol Bridge** establishing a serial message bridge between two PIC18F4580 controllers. Configured MCP2551 CAN transceivers at register-level to route serial data over a hardware CAN bus. |
| 🔗 [LPC2138-FreeRTOS-Semaphore-Mutex-Demo](https://github.com/Anandhu-AKR/LPC2138-FreeRTOS-Semaphore-Mutex-Demo) | **RTOS Resource & Task Coordinator** showcasing FreeRTOS counting semaphores and mutex locks on an ARM7 (LPC2138) MCU. Implements priority inheritance to prevent priority inversion during shared UART bus access. |
| 🔗 [GPS-Data-Parser-Arduino](https://github.com/Anandhu-AKR/GPS-Data-Parser-Arduino) | **Interrupt-Driven NMEA Parser** extracting latitude, longitude, and UTC timestamps from a GPS receiver. Processes incoming UART serial buffers and converts global coordinate references to Indian Standard Time (IST). |
| 🔗 [FIREBASE_DHT11](https://github.com/Anandhu-AKR/FIREBASE_DHT11) | **WiFi Telemetry Node** using ESP8266 to log DHT11 sensor data. Utilizes non-blocking network streams to upload sensor data periodically to a Firebase Realtime Database. |
| 🔗 [Automatic Door System PIR Arduino](https://github.com/Anandhu-AKR/Automatic-Door-System-PIR-Arduino) | **Event-Driven Actuation System** utilizing PIR sensors, a servo controller, and a 16x2 LCD display. Uses external pin interrupts (ISR) for motion triggers to save processor cycles. |
| 🔗 [PIC Microcontroller Projects](https://github.com/Anandhu-AKR/PIC_Microcontroller_Projects) | **Firmware Peripheral Library** containing code templates for ADC conversions, internal hardware timers, PWM duty cycle controls, and 7-segment/LCD displays for the PIC18 MCU series. |
| 🔗 [AVR Microcontroller Projects](https://github.com/Anandhu-AKR/AVR_Microcontroller_Projects) | **Register-Level AVR Library** featuring raw register configurations for timers, serial UART communication, SPI interfaces, and general GPIO manipulation on the ATmega series. |

---

## 🤖 Robotics & ROS 2 Middleware Projects

| 💡 Project | 🔍 Robotics Software & Middleware Details |
|---|---|
| 🔗 [ROS2_AGV_Core](https://github.com/Anandhu-AKR/ROS2_AGV_Core) | **10-Node Autonomous Warehouse AGV** system coordinating motor controls, IMU sensors, BMS diagnostics, and lidar navigation. Integrates a real-time glassmorphic HTML/JS cockpit dashboard using `rosbridge_websocket` for control commands and telemetry updates. |
| 🔗 [ROS2_Drone_Core](https://github.com/Anandhu-AKR/ROS2_Drone_Core) | **10-Node UAV Flight Telemetry Deck** managing altitude controls, GPS coordinates, compass headings, and battery diagnostics. Features a futuristic flight-cockpit web interface communicating with the flight controller node. |
| 🔗 [ROS2_Fusion_System](https://github.com/Anandhu-AKR/ROS2_Fusion_System) | **Multi-Sensor Data Fusion Hub** subscribing to concurrent IMU (tilt pitch/roll) and LiDAR (ground proximity) data streams. Fuses telemetry to evaluate safety alerts and publish real-time hazard flags. |
| 🔗 [ROS2_Collision_System](https://github.com/Anandhu-AKR/ROS2_Collision_System) | **Active Safety Controller** utilizing a simulated radar sensor publisher and an active guard evaluation subscriber to monitor safety distances and trigger warnings. |
| 🔗 [ROS2_Telemetry_System](https://github.com/Anandhu-AKR/ROS2_Telemetry_System) | **Robotic Kinematics Translator** demonstrating basic publish-subscribe communication. Converts rotational wheel encoder data (RPM) to linear velocity (m/s) using differential drive kinematics. |

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
