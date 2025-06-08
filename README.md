
# DIY Pulse Oximeter using MAX30102 and Arduino Nano

## Overview
This project demonstrates the construction of a DIY pulse oximeter using the MAX30102 sensor, an Arduino Nano, a 0.96” OLED display, and a push button. It is capable of displaying real-time heart rate and blood oxygen saturation (SpO₂) values.

## Features
- Real-time heart rate and SpO₂ monitoring
- OLED display for live output
- Push button to calculate and show average values
- Built using Arduino Nano and coded in C++ (Arduino IDE)
- Circuit prototyping done on breadboard

## Learning Outcomes
- Working with MAX30102 sensor for biomedical applications
- Using OLED screens with Arduino (SSD1306 via I²C)
- Basics of embedded C++ with Arduino IDE
- Creating circuit diagrams using Fritzing
- Debugging and replacing faulty hardware components

## Getting Started

### Hardware Required
- Arduino Nano
- MAX30102 Pulse Oximeter Sensor
- 0.96” OLED Display (I²C)
- Push Button
- Breadboard and Jumper Wires
- USB Cable for Arduino

### Software Required
- Arduino IDE
- Required Libraries:
  - `Wire.h`
  - `Adafruit_GFX.h`
  - `Adafruit_SSD1306.h`
  - `MAX30105.h` or `MAX3010x.h`
  - `heartRate.h` or `spo2_algorithm.h`

### Circuit Diagram
The circuit was prototyped on a breadboard. A Fritzing diagram (`.fzz file`) is available in the [`Schema`](./Schema) folder.

### How It Works
1. IR and Red LEDs on the MAX30102 detect changes in blood flow.
2. Arduino processes the data and calculates heart rate and SpO₂.
3. OLED displays real-time values.
4. Pressing the button shows average readings over a defined time window.

## Demo
Video demos are available in the [`Media`](./Media) folder (sensor in action).

