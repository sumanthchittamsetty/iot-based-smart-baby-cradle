# iot-based-smart-baby-cradle
ESP32-based IoT Smart Cradle that detects baby movement, crying, and moisture to automate rocking, play lullabies, and send real-time email alerts to parents.

Project Overview:

Designed and implemented an ESP32-based embedded IoT system to automate infant monitoring and response mechanisms using sensor integration, real-time processing, and cloud-based email alerts.

Technical Contributions:

Developed firmware for ESP32 microcontroller using Embedded C in Arduino IDE for real-time sensor data acquisition and control logic.

Integrated PIR/Motion Sensor to detect infant movement and implemented PWM-based motor control to automate cradle rocking.

Implemented cry detection algorithm using sound sensor input with threshold-based signal processing to differentiate ambient noise from sustained crying.

Programmed an event-driven response system to:

Trigger lullaby playback via audio module upon cry detection.

Send automated email notifications using SMTP protocol when crying exceeded predefined time limits.

Integrated a moisture sensor for hygiene monitoring and implemented conditional alert mechanisms for caregiver notification.

Designed modular code architecture separating sensing, processing, actuation, and communication layers.

Optimized power and response timing for reliable real-time operation.

Conducted hardware interfacing, circuit design, and testing of sensors, motor driver module, and ESP32 board.

Technologies & Tools:

ESP32, Embedded C, Arduino IDE, IoT (SMTP Email Protocol), PWM Motor Control, Sensor Interfacing, PIR Sensor, Sound Sensor, Moisture Sensor, DC Motor Driver
