# 🚀 ESP32 Smart Relay Controller

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) 
[![GitHub stars](https://img.shields.io/github/stars/yourusername/repo-name?style=social)](https://github.com/yourusername/repo-name)

> WiFi-enabled, multi-channel AC load controller designed using Altium Designer and ESP32.

---

## 📌 Overview

This project implements a **smart relay controller PCB** that can switch multiple AC loads using an **ESP32 microcontroller**.  
The controller supports:

- **WiFi-enabled control**
- **Manual switch inputs**
- **Relay isolation**
- Designed with AC/DC separation for safety

It’s ideal for smart homes, IoT automation, and AC load switching applications.

---

## 🧠 System Architecture

Each relay is driven through a ULN2003 transistor array, making the board capable of handling mains AC loads while protecting the ESP32 logic.

---

## 🛠️ Features

✔ Multi-channel AC load control  
✔ WiFi control via ESP32  
✔ Manual switch inputs supported  
✔ Electrical isolation with relays  
✔ Separate layout for AC and low-voltage DC  
✔ Wide PCB traces for load current  
✔ Designed with proper clearance

---

## 📦 Hardware Components

| Component     | Description                         |
|---------------|-------------------------------------|
| ESP32         | Main controller (WiFi + GPIO)       |
| ULN2003       | Relay driver IC                     |
| 5V Relays     | Switch high-voltage AC loads        |
| AC-DC Module  | Converts mains to DC                |
| Voltage Regs  | 5V / 3.3V supply for logic          |
| Pull-up Resistors | For stable switch inputs         |
| Terminal Blocks | AC input/output connections       |
| Programming Header | For firmware programming       |

---

## 📁 Project Structure

```
ESP32-Smart-Relay-Controller/
├── Schematic/
│   └── SmartRelay.SchDoc
├── PCB/
│   └── SmartRelay.PcbDoc
├── Output/
│   └── Gerber/
├── Images/
│   ├── PCB_Top.png
│   ├── PCB_Bottom.png
│   └── 3D_View.png
└── README.md
```
---

## 🖼️ PCB Preview

![PCB Top](./Images/PCB_Top.png)  
![PCB Bottom](./Images/PCB_Bottom.png)  
![3D View](./Images/3D_View.png)

---

## ⚡ Applications

✔ Smart Home Automation  
✔ Remote Lighting Control  
✔ Industrial Load Switching  
✔ IoT Appliance Management

---


