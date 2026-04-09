# 🗑️ Smart Dustbin using Arduino

## 📖 Overview

This project is a **Smart Automatic Dustbin** that opens its lid when a user comes near and sends an alert message when the dustbin is full.

It is built using Arduino, Ultrasonic Sensor, IR Sensor, Servo Motor, and GSM module.

---

## ⚙️ What This Code Does

### 🔹 1. Automatic Lid Opening

* The **Ultrasonic Sensor** measures distance.
* If a hand/object is detected within **10 cm**:

  * The **servo motor opens the lid**
  * After 9 seconds, the lid **closes automatically**

---

### 🔹 2. Dustbin Full Detection

* The **IR Sensor** detects if the dustbin is full.
* When full:

  * A message is sent using **GSM module**
  * Message: *"The dustbin is full. Please empty it."*

---

### 🔹 3. SMS Alert System

* Uses `SoftwareSerial` to communicate with GSM
* Sends SMS to a predefined phone number
---

## 🛠️ Components Used

* Arduino Uno
* Ultrasonic Sensor (HC-SR04)
* IR Sensor
* Servo Motor
* GSM Module
* Jumper Wires
---

## 🎯 Key Features

* Touchless dustbin operation
* Automatic lid control
* Full-level detection
* SMS alert notification


