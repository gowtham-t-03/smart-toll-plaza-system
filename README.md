# smart-toll-plaza-system
# Smart Toll Plaza System using ESP32

This project implements a smart toll plaza system using ESP32, RFID technology, and multiple sensors for automated vehicle detection and toll collection.

## Features
- RFID based toll payment
- Automatic vehicle classification (car / truck)
- Dual lane management
- Servo controlled toll gates
- WiFi based monitoring API
- LCD display for lane suggestion
- Tailgating detection
- EV priority mode

## Hardware Components
- ESP32
- MFRC522 RFID Reader
- Ultrasonic Sensors
- IR Sensors
- Servo Motors
- I2C LCD Display
- Buzzer

## Technologies Used
- Arduino / Embedded C++
- ESP32 WiFi
- RFID Communication
- Ultrasonic sensing
- Web server API

## Working
1. Vehicle enters lane and triggers IR sensor.
2. Ultrasonic sensor measures vehicle height.
3. Vehicle is classified as car or truck.
4. RFID card is scanned for payment.
5. Balance is deducted and gate opens.
6. Data can be monitored through WiFi API.
