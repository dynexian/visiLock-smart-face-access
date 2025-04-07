# visiLock-smart-face-access
VisiLock: Smart Face Access System A secure IoT-based door lock system using face recognition with ESP32-CAM. It eliminates the need for physical keys, allowing remote access via a web app. Built for homes, offices, and institutions needing modern access control.

VisiLock is an IoT-powered smart access control system that uses face recognition for secure, keyless entry. Built using the ESP32-CAM module and integrated with a web-based control app, it provides a modern, user-friendly solution for access management.

---

## 🚀 Features

- 🔍 Face Recognition Authentication
- 🌐 IoT-based Web Control (ESP32 + WiFi)
- 📱 Remote Door Lock Management
- 🔒 Enhanced Security Without Physical Keys
- 🖥️ Web Interface for Admins
- ⚡ Low-cost, scalable solution for homes, offices, institutions

---

## 🧠 Tech Stack

- ESP32-CAM (Microcontroller)
- Arduino IDE (C++)
- Web App (HTML/CSS/JS or Flask)
- Firebase / Local DB for Logs (optional)
- WiFi Connectivity
- Servo Motor/Relay for Lock Mechanism

---

## 📸 Project Preview

> *(Add photos or video demo gif here)*

---

## 💡 Use Cases

- Residential Security
- Office Access Management
- Server Room Entry
- Co-working Spaces
- Healthcare Facilities
- Hotels, Hostels & More

---

## 📅 Project Duration

> June 2024 – August 2024  
> Developed as a part of academic & personal IoT experimentation

---

## 🙋‍♂️ Developed By

**Shubham R. Vishwakarma**  
📍 Rourkela, Odisha | 💻 Diploma in IT  
[LinkedIn](https://www.linkedin.com/in/shubham-r-vishwakarma) | [Email](mailto:vishwakarmashubham2004@gmail.com)

---

## 📜 License

MIT License

🚀 Setup Instructions for ESP32-CAM (VisiLock Project)
Hardware Connections

Follow the circuit diagrams from the report.

Connect FTDI to ESP32-CAM properly.

Use a Type B mini USB port to connect FTDI to your laptop.

Install Software

Install Arduino IDE.

Go to Tools > Board > Boards Manager → Search "ESP32" by Espressif Systems → Install v1.0.5 (⚠️ Important).

Install CH340 COM Port Driver.

Board Configuration

Go to Tools > Board → Select "ESP32 Wrover Module".

Install "ArduinoWebSockets" library by Gil Maimon from Library Manager.

Tool Settings (in Arduino IDE)

Board: ESP32 Wrover Module

Port: Select the correct port (FTDI connected ESP32)

Flash Frequency: 80 MHz

Flash Mode: QIO

Partition Scheme: Huge APP (3MB No OTA / 1MB SPIFFS)

Upload Speed: 921600

Upload Code

Open FaceDoorEntryESP32Cam/FaceDoorEntryESP32Cam.ino in Arduino IDE.

Edit the file to add your Wi-Fi SSID and Password.

Verify and Upload the code.

Test

Open Serial Monitor → Set baud rate to 115200.

Turn on mobile hotspot (same credentials as in code).

ESP32 will connect and show IP Address → Open it in a web browser.
