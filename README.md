📡 Real-Time Structural Health Monitoring using ESP32
🔎 Project Overview

This project presents a Real-Time Structural Health Monitoring (SHM) system developed using an ESP32 microcontroller and an accelerometer sensor. The system continuously monitors structural vibrations and detects abnormal movement patterns that may indicate structural damage or instability.
The main aim of this system is to ensure safety by providing early detection of structural issues in buildings, bridges, and other infrastructure.

🎯 Objectives

To measure real-time vibration data using an accelerometer sensor
To process and analyze sensor data using ESP32
To detect abnormal structural movement
To provide early warning for possible structural damage.

🛠 Hardware Components

ESP32 Microcontroller (with inbuilt WiFi)
Accelerometer Sensor (MPU6050)
DHT11 Temperature & Humidity Sensor
Power Supply
Jumper Wires
Breadboard

⚙️ Working Principle

The accelerometer sensor (MPU6050/ADXL345) is mounted on the structure to continuously measure vibration and movement along the X, Y, and Z axes.
The DHT11 sensor monitors environmental conditions such as temperature and humidity, which can also affect structural stability over time.
The ESP32 microcontroller reads real-time data from both sensors using I2C or digital communication protocols.
The collected vibration data is analyzed to determine the amplitude and frequency of structural movement.
The system compares the measured vibration values with predefined threshold limits to detect abnormal structural behavior.
If vibration levels exceed the safe threshold, the ESP32 identifies it as a potential structural anomaly or damage condition.
Using the built-in WiFi module of ESP32, the monitored data can be transmitted to a cloud platform or web dashboard for remote monitoring and analysis.

🚀 Features

Real-time vibration monitoring
Wireless communication support
Low-cost and scalable system
Early structural fault detection

📈 Future Enhancements

Cloud data storage
Mobile app integration
Machine learning-based damage prediction
Automated alert notification system
