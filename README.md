# Sumanth H D – Embedded Systems Engineer

![License](https://img.shields.io/badge/status-Active-brightgreen)
![Platform](https://img.shields.io/badge/platform-Embedded%20Systems-blue)

## 🚀 About the Project

This repository showcases a collection of embedded systems and IIoT (Industrial IoT) projects developed by **Sumanth H D**, a skilled embedded engineer with hands-on experience in firmware development, real-time systems, driver programming, and hardware-software integration using microcontrollers like **ESP32**, **STM32**, and **Raspberry Pi CM4**.

## 🧠 Key Projects

### 🛠️ 1. Eagle Mini (IIoT Gateway)
- **Platform**: ESP32-WROOM
- **Tools**: ESP-IDF, FreeRTOS, Arduino
- **Highlights**:
  - Interfaced GSM, energy meter, CNC signals via GPIO
  - Stored and pushed data to the cloud via HTTPS
  - Real-time edge gateway for manufacturing industries

### 📈 2. IIOT CNC Monitoring System
- **Platform**: Raspberry Pi CM4
- **Tools**: Python3, SQLite, Linux, GitHub
- **Highlights**:
  - Collected machine signals
  - Local + cloud database syncing
  - API integration with a React-based front-end

### 💻 3. Bare-Metal Driver Development
- **Platform**: STM32F407VGT6
- **Tools**: Embedded C, STM32CubeIDE, Keil IDE
- **Drivers Developed**: UART, SPI, I2C, ADXL345 Sensor, EEPROM
- **Techniques**: Polling & Interrupts, ADC, Timers, PWM

---

## 🧰 Skills

- **Languages**: C, Embedded C, Python
- **Microcontrollers**: ESP32, STM32 (ARM Cortex-M4), Raspberry Pi CM4
- **Tools/IDEs**: Keil IDE, STM32CubeIDE, GCC, Visual Studio
- **Protocols**: UART, SPI, I2C, RS232, RS485, CAN
- **OS & Frameworks**: FreeRTOS, Linux, Shell Scripting

---

## 🧪 How to Use

```bash
# Clone the repository
git clone https://github.com/your-username/charan-embedded-projects.git

# Explore each project folder
cd project-name

# For ESP32 projects (with ESP-IDF)
idf.py build && idf.py flash monitor

# For Python-based Raspberry Pi projects
python3 main.py
