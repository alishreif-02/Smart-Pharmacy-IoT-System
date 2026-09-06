# Smart Pharmacy IoT System

IoT-based medication-management system using **ESP32**, **Android / Java**, sensors, servo-controlled compartments, LED guidance, audio alerts, and Wi-Fi communication.

## Overview

The Smart Pharmacy project is an embedded and IoT system designed to support medication organisation and reminders.

The system combines a physical smart medicine cabinet with software-based control and monitoring.

Its design focuses on practical medication management and accessibility, including visual and audio guidance.

## Main Features

- ESP32-based embedded controller
- Servo-controlled medicine compartments
- LED guidance
- Sensor-based interaction
- Audio / voice alerts
- Wi-Fi communication
- Android application integration
- Medication reminders
- Accessibility-focused interaction

## System Concept

```text
Android Application
        ↓
   Wi-Fi Communication
        ↓
       ESP32
   ┌────┼─────┐
   ↓    ↓     ↓
Servos LEDs Sensors
   ↓
Medicine Compartments
   ↓
Audio / Visual Alerts
```

## Hardware

The system uses an ESP32 as the main embedded controller.

Depending on the prototype configuration, components include:

- ESP32 development board
- Servo motors
- LEDs
- Sensors
- Audio output / buzzer or speaker components
- Medication storage compartments
- Power supply and wiring

## Software

### ESP32 Firmware

The embedded code controls:

- Servo movement
- LED behaviour
- Sensor input
- Alert logic
- Wi-Fi communication
- Medicine-compartment actions

### Android Application

The Android side is designed to support functions such as:

- Medication scheduling
- Reminder configuration
- User interaction
- Communication with the smart cabinet
- Remote monitoring concepts

## Accessibility

A key design goal was to make the system useful to users with different accessibility needs.

The prototype explored:

- **Visual guidance** using LEDs
- **Audio guidance** for users who may have difficulty reading visual information
- Simple physical interaction
- Automated compartment opening

## Technologies

- ESP32
- Arduino / C++
- Java
- Android
- IoT
- Wi-Fi Communication
- Servo Motors
- Sensors
- LEDs
- Embedded Systems
- Accessibility-Focused Design

## Repository Structure

```text
smart-pharmacy-iot/
│
├── README.md
├── Smart_Pharmacy_ESP32.ino
├── android/              # Add Android source files if available
├── docs/                 # Report, poster, diagrams
└── images/               # Prototype photographs
```

## How to Run the ESP32 Code

1. Install the Arduino IDE.
2. Install ESP32 board support.
3. Open:

```text
Smart_Pharmacy_ESP32.ino
```

4. Select the correct ESP32 board and COM port.
5. Update Wi-Fi configuration if required.
6. Connect the required hardware components.
7. Upload the firmware to the ESP32.
8. Open the Serial Monitor for debugging.

## Engineering Challenges

The project involved combining software and hardware into one working system.

Important challenges included:

- Coordinating servo movement
- Managing sensor inputs
- Connecting the ESP32 over Wi-Fi
- Designing clear user alerts
- Integrating multiple hardware components
- Designing a system around real user needs

## Future Improvements

- Add secure cloud-based medication records
- Improve Android application design
- Add push notifications
- Add user authentication
- Add caregiver / family notifications
- Store medication history
- Add missed-dose detection
- Add battery and connectivity monitoring
- Improve the physical enclosure
- Add voice-assistant integration

## What I Learned

This project strengthened my practical experience with:

- Embedded programming
- ESP32 development
- IoT communication
- Hardware / software integration
- Servo and sensor control
- Android development concepts
- Designing technology around accessibility needs

## Author

**Ali Shreif**

IoT / Embedded Systems / Software Engineering portfolio project.
