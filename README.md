# ESP32-Smart-Relay-Controller
WiFi based multi-channel AC load controller using ESP32 and ULN2003
🚀 ESP32 Based Smart Relay Controller
📌 Project Overview

This project is a WiFi-enabled multi-channel AC load controller designed using Altium Designer.
It allows switching of multiple AC appliances using an ESP32 microcontroller, relay drivers, and electromechanical relays.

The system can be controlled:

📶 Via WiFi (ESP32)

🔘 Via external manual switches

🧠 System Architecture

ESP32 → ULN2003 Driver → Relay → AC Load

The ESP32 controls relay channels through a ULN2003 Darlington transistor array, which safely drives the relay coils to switch high-voltage AC loads.

⚙️ Hardware Components Used

ESP32 (WiFi Microcontroller)

ULN2003 Relay Driver IC

5V Electromechanical Relays

AC-DC Power Supply Module

Voltage Regulator (5V / 3.3V)

Pull-up Resistors

Screw Terminal Connectors

Programming Header

Mounting Holes

🔌 Features

✅ Multi-channel AC load control

✅ WiFi-enabled automation capability

✅ Manual switch input support

✅ Electrical isolation using relays

✅ Dedicated relay driver stage

✅ Separate AC and DC sections in PCB layout

✅ Designed with proper clearance for high-voltage safety

🛠️ PCB Design Details

Designed using Altium Designer

2-layer PCB

Separate AC and low-voltage DC routing

Wide traces for AC load current

Decoupling capacitors near ESP32

Proper ground routing for noise reduction

📂 Project Files Included

📄 Schematic File (.SchDoc)

🟫 PCB Layout File (.PcbDoc)

📦 Project File (.PrjPcb)

🏭 Manufacturing Output (Gerber Files)

📷 PCB Top & Bottom Images

⚡ Applications

Smart home automation

Remote lighting control

Industrial load switching

IoT-based appliance control
