# Automatic Power Cut-Off Timer for Electronic Device Protection

## Overview

The **Automatic Power Cut-Off Timer** is an Arduino-based embedded systems project designed to help prevent **overheating and overcharging** of electronic devices such as laptops, smartphones, and other appliances. The system uses a **servo motor** to physically operate a power switch and can be controlled remotely through a **Bluetooth-enabled Android application** developed using **MIT App Inventor**.

This project demonstrates embedded programming, Bluetooth communication, hardware interfacing, and mobile application development.

---

## Academic Project

This project was developed as part of the **Design Thinking and Innovation (DTI)** course. The objective was to design and implement a practical embedded systems solution that enables users to remotely control the power supply to electronic devices, helping reduce overheating and unnecessary charging.

---

## Features

- Bluetooth-based remote power control
- Servo motor-operated physical switch
- Android application developed using MIT App Inventor
- Helps reduce overheating and overcharging
- Simple, low-cost, and user-friendly embedded system

---

## Components Used

- Arduino Uno
- HC-05 Bluetooth Module
- Servo Motor
- 5V Battery
- Jumper Wires
- Android Smartphone

---

## Software Used

- Arduino IDE
- Arduino C/C++
- MIT App Inventor

---

## Working Principle

1. The Arduino Uno and servo motor are powered using a 5V battery.
2. The HC-05 Bluetooth module establishes communication between the Arduino Uno and the Android application.
3. The user connects to the HC-05 module using the **Connect** button in the mobile application.
4. When the **ON** button is pressed, the application sends the **"ON"** command via Bluetooth.
5. The Arduino receives the command and rotates the servo motor to **90°**, physically turning the power switch ON.
6. When the **OFF** button is pressed, the application sends the **"OFF"** command.
7. The Arduino rotates the servo motor back to **0°**, switching the power OFF.

---

## Project Structure

```text
Automatic-Power-Cut-Off-Timer/
│
├── Arduino_Code/
│   └── Automatic_Power_Cut_Off_Timer.ino
│
├── Project_Demo/
│   ├── Project_Setup.jpg
│   ├── Circuit_Diagram.png
│   └── App_Interface.png
│
└── README.md
```

---

## Project Demonstration

### Hardware Setup

<img src="Project_Demo/Project_Setup.jpeg" alt="Hardware Setup" width="600">

### Circuit Diagram

<img src="Project_Demo/Circuit_Diagram.png" alt="Circuit Diagram" width="700">

### Mobile Application Interface

<img src="Project_Demo/App_Interface.jpeg" alt="Mobile App Interface" width="250">

---

## Applications

- Smart home automation
- Remote power management
- Prevention of overheating and overcharging
- Embedded systems learning and academic projects

---

