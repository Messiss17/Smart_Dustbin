**SMART WASTE SEGREGATION DUSTBIN**

**📘 Project Overview**

The Smart Waste Segregation Dustbin is an Arduino-based automation system that detects incoming waste and automatically classifies it into Wet or Dry categories. Using an ultrasonic sensor for detection and a soil-moisture sensor for classification, the system rotates a servo-controlled flap to drop the waste into the correct bin.
This project aims to make waste disposal more hygienic, efficient, and environmentally friendly.

**💡 Why We Chose This Project**

Improper waste segregation is a major challenge in homes and public spaces.

Manual segregation is unhygienic, time-consuming, and often ignored.

Automated sorting reduces human effort and encourages proper disposal.

Helps support recycling and smart-city cleanliness initiatives.

A great practical learning project using Arduino, sensors, and automation.

**🌍 Main Use for People**

Promotes Hygiene: No need to touch the bin; waste is sorted automatically.

Reduces Workload for Sanitation Workers: Pre-segregated waste is easier to handle.

Supports Recycling: Wet and dry waste separation improves recycling efficiency.

Ideal for Public Places: Schools, hospitals, hostels, offices, railway stations, etc.

Educates Users: Encourages proper waste disposal habits.

**⚙️ How It Works**

Object Detection:
The ultrasonic sensor measures the distance. When waste is detected within 10 cm, the system activates.

Moisture Analysis:
The soil-moisture sensor checks the moisture level.

Moisture < 50 → Wet Waste

Moisture ≥ 50 → Dry Waste

Servo Movement:
The servo rotates:

0° → Wet Waste bin

180° → Dry Waste bin
It then returns to 90° (neutral position).

LCD Display:
Shows real-time messages like

“WET Waste”

“DRY Waste”

“Smart Dustbin”

Serial Monitor:
Displays distance and detection information for debugging.

**🔧 Built With (Arduino Project Info)**
**Hardware Components:**

Arduino Uno/Nano

Ultrasonic Sensor (HC-SR04)

Soil Moisture Sensor

Servo Motor (SG90/MG995)

16x2 I2C LCD Display

Jumper Wires & Prototype Dustbin

**Software:**

Arduino IDE

**Libraries:**
Servo.h

LiquidCrystal_I2C.h

**Programming Highlights**

Distance measurement using pulseIn()

Moisture measurement using analogRead()

Sensor mapping using map()

Servo angle control for waste direction

LCD display for user feedback
