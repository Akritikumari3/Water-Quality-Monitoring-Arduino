# Water Quality Monitoring System using Arduino UNO

A TDS-based water quality monitoring system built with Arduino UNO that measures the purity of water in real-time and displays the results on a 16x2 LCD screen. This project aims to promote water sustainability using low-cost embedded technology.

##  Table of Contents

- [Overview](#overview)
- [Hardware Components](#hardware-components)
- [Circuit & Block Diagram](#circuit--block-diagram)
- [Working Principle](#working-principle)
- [Features](#features)
- [How to Use](#how-to-use)
- [Demo Video](#demo-video)

##  Overview

This micro project uses a Total Dissolved Solids (TDS) sensor interfaced with an Arduino Uno and a 16x2 LCD to display the TDS level of water. The system is intended for water filtration systems, home water testing, and environmental quality monitoring.

##  Hardware Components

- Arduino UNO  
- TDS Sensor Module  
- 16x2 LCD Display  
- Breadboard & Jumper Wires  
- USB Cable for Arduino

##  Circuit & Block Diagram

- `circuit_diagram.png` — Shows connection between Arduino, TDS sensor, and LCD  
- `block_diagram.png` — Represents system architecture at a high level

##  Working Principle

1. The TDS sensor detects water conductivity.  
2. The Arduino reads this analog signal and converts it to digital.  
3. A calibrated formula calculates the TDS value in ppm.  
4. The LCD displays the real-time TDS value.  
5. If the TDS value > 300 ppm, a warning is shown on the screen.

##  Features

- Real-time water quality monitoring  
- LCD output for instant feedback  
- TDS threshold alert  
- Compact and cost-efficient  
- Extendable with pH, turbidity sensors & IoT modules

##  How to Use

1. Upload `water_quality_monitor.ino` to your Arduino using the Arduino IDE.  
2. Wire components as per the provided `circuit_diagram.png`.  
3. Power the system via USB or battery.  
4. Observe real-time TDS values on the LCD.

## 🎥 Demo Video

 [Watch Project Demo Here](https://github.com/Akritikumari3/Water-Quality-Monitoring-Arduino)

##  Code & Resources

- `water_quality_monitor.ino` – Arduino sketch file  
- `circuit_diagram.png` – Full circuit layout  
- `block_diagram.png` – System architecture overview

✅ **Project source code and files are uploaded on GitHub in this repository.**


