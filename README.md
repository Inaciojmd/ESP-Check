# ⚠️ Advanced ESP Hardware Detection & Analysis Tool ⚙️

![Banner](https://user-images.githubusercontent.com/12345678/esp_banner.png)

> **Version**: `v3.0`  
> **Author**: `👤 DaylorSec`  
> **License**: MIT  
> **Tags**: `ESP32`, `ESP8266`, `MicroPython`, `Arduino`, `Hardware Scanner`, `USB Analysis`, `Cyber Diagnostic`

---

## 💀 Description

> **_Scan. Analyze. Dominate._**

This script is a **multi-layer ESP hardware detection tool**, designed to deeply analyze USB-connected ESP devices (ESP32, ESP8266) with terrifying precision.

- 🧠 Auto-detects all serial/USB devices
- 🔬 Extracts CPU, Flash, MAC, and Partition data
- ☁️ Fetches real-time update info from GitHub
- 💥 Supports MicroPython, Arduino, and raw firmware detection
- 👁️‍🗨️ Generates complete technical reports
- 🧪 Advanced diagnostics commands included

---

## 🧠 Features

| Category       | Capability |
|----------------|------------|
| 🔌 USB Scan     | Lists connected USB devices with Vendor/Product/Serial |
| 🧿 ESP Detection | Identifies CP210x, CH340, FTDI bridges |
| 💻 CPU Info     | Gets ESP chip type, cores, and WiFi/Bluetooth features |
| 💾 Flash Memory | Manufacturer, device type, and size detection |
| 🧱 Partitions   | Reads and parses partition tables |
| 📶 WiFi Check   | Identifies monitor mode, AP/STA dual ops |
| 📳 Bluetooth    | BLE, Classic, or None based on chip |
| 🔍 Firmware     | Detects MicroPython & Arduino frameworks |
| 🔁 Updates      | Gets latest firmware releases via GitHub API |
| 📝 Report       | Generates complete hardware diagnostic reports |
| 💣 Tools        | Lists recommended toolchain for development |

---

## 🖥️ Requirements

Install dependencies:

```bash
pip install pyserial colorama requests packaging pyusb