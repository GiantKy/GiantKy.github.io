---
title: "Arduino LM35 Temperature Monitoring System"
collection: portfolio
permalink: /portfolio/portfolio-1/
excerpt: "A simple embedded system project using Arduino UNO and LM35 sensor to measure and display temperature in real time."
date: 2026-04-15
author_profile: true
---

# Arduino LM35 Temperature Monitoring System

## Project Overview
This project is an embedded system built using **Arduino UNO** and **LM35 temperature sensor**.  
It reads analog temperature values and displays them via Serial Monitor.

---

## Features
- Real-time temperature measurement
- Analog-to-digital conversion (ADC)
- Serial communication with PC
- Easy to extend for IoT applications

---

## Hardware Used
- Arduino UNO
- LM35 Temperature Sensor
- Breadboard & jumper wires
- USB cable

---

## Software Used
- Arduino IDE
- Serial Monitor

---

## How It Works
1. LM35 outputs analog voltage proportional to temperature  
2. Arduino reads analog signal via A0 pin  
3. Converts ADC value into temperature (°C)  
4. Displays result on Serial Monitor  

---

## Source Code
GitHub Repository:  
https://github.com/GiantKy/Arduino_LM35_TempMonitor

---

## Future Improvements
- Add ESP8266/ESP32 for IoT cloud monitoring  
- Display data on web dashboard  
- Store data in database (Firebase / MQTT)

---

## Skills Applied
- Embedded C programming  
- Sensor integration  
- ADC conversion  
- Serial communication