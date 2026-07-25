# 🏗️ Hardware Architecture

## System Overview

The Railway Track Crack Detection System is built around a Raspberry Pi 4, which acts as the central controller. A Raspberry Pi Camera continuously captures images of the railway track while the robot moves. These images are processed using OpenCV to detect cracks. If a crack is detected, the system generates an alert for maintenance.

---

## Hardware Flow

Power Supply
      ↓
Raspberry Pi 4
      ↓
Pi Camera → Image Processing (OpenCV)
      ↓
Crack Detection
      ↓
Alert / Save Image

---

## Main Modules

- Raspberry Pi 4
- Raspberry Pi Camera
- Motor Driver (L298N)
- DC Motors
- Battery Pack
- Robot Chassis

---

## Future Expansion

- GPS Module
- GSM Alert System
- IoT Dashboard
- AI-based Crack Classification
