# Smart Home Fan Control System

This project implements an **automatic fan control system** based on room temperature using an LM35 temperature sensor and Arduino microcontroller. The fan speed is adjusted dynamically using PWM.

## Features
- Temperature sensing using LM35
- Automatic fan speed control via PWM
- Embedded C programming on Arduino
- Simple smart home application

## Hardware Requirements
- Arduino Uno (or compatible microcontroller)
- LM35 Temperature Sensor
- Small DC Fan
- Relay
- Jumper Wires
- Breadboard (optional)
- USB Cable for power & Serial Monitor

## Software Requirements
- Arduino IDE
- Embedded C

## Circuit
- LM35 VCC → 5V
- LM35 GND → GND
- LM35 OUT → A0 (analog input)
- Arduino PWM pin (e.g., D9) → Enable pin on L293D / relay module
- Relay outputs → DC Fan terminals
- Common GND
- USB → PC for Serial Monitor (optional)

## Tools & Technologies
- Arduino IDE
- Embedded C
