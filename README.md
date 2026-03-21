<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=Aman%20Kumar&fontSize=55&fontColor=ffffff&fontAlignY=38&desc=Embedded%20Systems%20%7C%20Firmware%20Engineer%20%7C%20IoT&descSize=18&descAlignY=58" />

</div>

---

# 👋 Hi, I'm Aman Kumar

🔧 **Embedded Systems & Firmware Engineer**  
🚗 **Automotive / IoT Systems | Bare-Metal Development | Secure Connectivity**

---

## 🧑‍💻 About Me

```c
struct Engineer {
    const char* role = "Embedded Systems & Firmware Engineer";
    const char* domain = "Automotive & Cellular IoT";
    const char* education = "B.Tech ECE — VIT Vellore";

    const char* experience[] = {
        "Embedded Systems Intern @ CNH Industrial",
        "IoT Systems & Real-Time Firmware Development"
    };

    const char* focus[] = {
        "Bare-metal firmware",
        "Peripheral driver development",
        "Secure device-to-cloud communication"
    };

    const char* current_work = "Building production-grade embedded systems (MCU → Cloud)";
};

```
---


## 🏭 Industry Experience

### 🔹 Embedded Systems Intern — CNH Industrial

<div align="center">

⚡ **Built a production-grade embedded telematics system from hardware bring-up to secure cloud communication**

</div>

---

### 🚧 Challenge
- Bringing up a **bare-metal system** on a new MCU (**PIC32CX SG61**)  
- Integrating **cellular communication (EC200U-CN)** with unstable network conditions  
- Handling **secure communication (TLS/mTLS)** on constrained embedded hardware  
- Debugging **real-world failures** (AT commands, SSL handshake, payload issues)

---

### ⚙️ What I Did
- Performed **bare-metal MCU bring-up**
- Developed drivers:
  - GPIO, UART, SPI, I²C, ADC, PWM, Timers, Interrupts
- Integrated **cellular + GPS module (EC200U)**
- Built **cloud communication pipeline**:
  - MQTT, HTTPS
  - TLS / mTLS authentication
- Debugged:
  - Network failures
  - SSL/TLS handshake issues
  - Data formatting & transmission bugs

---

### 🚀 Impact / Outcome
- Enabled **reliable telemetry data transmission** from device → cloud  
- Improved **system stability under real network conditions**  
- Delivered a **fully integrated IoT pipeline** (hardware → firmware → cloud)  
- Gained hands-on experience in **production-level debugging & system integration**

---

### 🔹 IoT Intern — Seculinx  
**Sep 2024 – Jan 2025 | Vellore**

- Developed **sensor-based smart lighting system**
- Used **ESP32 + multi-sensor inputs**
- Built adaptive control logic for **energy optimization**
- Focused on **modular firmware & system reliability**

---

### 🔹 Embedded Intern — Maven Silicon  
**Jun 2024 – Jul 2024**

- Built **wearable obstacle detection system**
- Used **Arduino Nano + ultrasonic sensors**
- Designed real-time alert system (buzzer feedback)
- Improved detection accuracy via calibration & testing

---
## 🛠️ Tech Stack

### 🔧 Embedded & Firmware

<div align="center">

![PIC32](https://img.shields.io/badge/PIC32CX-0A0A0A?style=for-the-badge)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Bare Metal](https://img.shields.io/badge/Bare--Metal-FF6F00?style=for-the-badge)
![Drivers](https://img.shields.io/badge/Peripheral%20Drivers-00599C?style=for-the-badge)
![Debugging](https://img.shields.io/badge/Low--Level%20Debugging-8E44AD?style=for-the-badge)

</div>

---

### 🌐 Connectivity & Protocols

<div align="center">

![UART](https://img.shields.io/badge/UART-2C3E50?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-1ABC9C?style=for-the-badge)
![I2C](https://img.shields.io/badge/I2C-3498DB?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=eclipse-mosquitto&logoColor=white)
![HTTPS](https://img.shields.io/badge/HTTPS-27AE60?style=for-the-badge)
![TLS](https://img.shields.io/badge/TLS%2FmTLS-C0392B?style=for-the-badge)
![EC200U](https://img.shields.io/badge/Cellular%20IoT-EC200U-34495E?style=for-the-badge)

</div>

---

### 🛠️ Tools & Workflow

<div align="center">

![MPLAB](https://img.shields.io/badge/MPLAB%20X-DD0031?style=for-the-badge)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Logic Analyzer](https://img.shields.io/badge/Logic%20Analyzer-7F8C8D?style=for-the-badge)
![Serial Debug](https://img.shields.io/badge/Serial%20Debugging-16A085?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

----

## 🚀 Featured Project

<div align="center">

### 🔹 bare-metal-programming-guide

⚙️ **From MCU boot → register-level control → real-world debugging**

<a href="https://github.com/Aman-Kumar-19/bare-metal-programming" target="_blank">
  <img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

### 🚧 Problem / Challenge
- Most resources are **theory-heavy** and not aligned with real firmware work  
- Lack of clarity in:
  - MCU startup sequence  
  - Linker scripts & memory layout  
  - Debugging real embedded failures  

---

### ⚙️ What This Project Does
- Explains **bare-metal firmware from scratch → step-by-step**
- Covers:
  - MCU boot process & startup code  
  - Linker scripts (FLASH / RAM layout)  
  - Register-level peripheral programming  
  - Interrupt handling & NVIC  
  - ADC (Polling vs DMA)  
- Demonstrates **real debugging scenarios and fixes**

---

### 🚀 Engineering Impact
- Bridges gap between **theory and production firmware development**  
- Helps engineers transition from:
  - High-level coding → **low-level system understanding**  
- Structured like **industry-grade firmware documentation**

---

### 🧠 Why It Stands Out
- Not just “how it works” → **why it breaks & how to fix it**  
- Focus on **edge cases, failures, and debugging mindset**  
- Built from **hands-on embedded experience (not copied tutorials)**  

---

## 🧩 Engineering Projects

---

### 🔹 🚗 Vehicle Telemetry Platform

<div align="center">

<a href="https://github.com/Aman-Kumar-19/vehicle-telemetry-platform" target="_blank">
  <img src="https://img.shields.io/badge/View%20Project-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

- Built a **software-based simulation of an automotive CAN network**
- Emulates multiple ECUs transmitting **real-time CAN frames**
- Developed a **CAN analyzer** for decoding and visualizing vehicle data  
- Demonstrates:
  - ECU communication patterns  
  - CAN message structures  
  - Automotive system-level behavior  

---

### 🔹 🔌 DC-DC Power Converter PCB

<div align="center">

<a href="https://github.com/Aman-Kumar-19/DC-DC-Power-Converter-PCB" target="_blank">
  <img src="https://img.shields.io/badge/View%20Design-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

- Designed a **+5V → +3.3V voltage regulation PCB**
- Focused on:
  - Power efficiency  
  - Stable voltage output  
  - Component selection & layout optimization  
- Implemented using **Altium Designer**

---

### 🔹 ⚙️ Embedded & IoT Systems

- **Smart Lighting Automation System**  
  → Sensor-based adaptive lighting using real-time inputs  

- **Wearable Obstacle Detection System**  
  → Real-time obstacle alerts using ultrasonic sensing  
  🔗 https://github.com/Aman-Kumar-19/Obstacle-Detection-Blind  

- **Bare-metal Driver Development**  
  → Register-level peripheral programming and validation  
  🔗 https://github.com/Aman-Kumar-19/bare-metal-programming  

 

---

### 🔹 🔬 Research Work

- **Fast Slepian Transform for Spectrum Sensing**  
  📄 DOI: https://doi.org/10.1109/ACCESS.2025.11115038  

- **Hybrid Cryptographic Model (AES–DES–RSA)**  
  📄 DOI: https://doi.org/10.1038/s41598-025-21861-2  

---



## 🎯 Current Focus

- ⚙️ Optimizing **bare-metal firmware** for performance, memory, and reliability  
- 🔧 Designing **efficient peripheral drivers** (interrupt-driven & low-latency systems)  
- 🌐 Building **secure cellular IoT pipelines** (device → cloud using MQTT, TLS/mTLS)  
- 🧠 Developing **production-grade embedded architectures** with clean, scalable design  

---

## 📫 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/aman-kumar-413838239/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="mailto:amankr20001@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
</a>
&nbsp;
<a href="https://github.com/Aman-Kumar-19" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
&nbsp;
<a href="https://aman-kumar-19.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio" />
</a>

<br/><br/>

> ⚙️ *Engineering reliable embedded systems — from bare-metal firmware to secure cloud connectivity*

<!-- Footer Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=120&section=footer" />

</div>
