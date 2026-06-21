# 🚗 Alcohol Detection and Engine Locking System 

## 📌 Overview

The Alcohol Detection and Engine Locking System is an Arduino-based safety project designed to prevent intoxicated driving. The system uses an MQ3 Alcohol Sensor to detect alcohol vapors from a driver's breath. If the alcohol concentration exceeds a predefined threshold, the system activates a buzzer and locks the engine using a relay module.

This project aims to improve road safety by preventing accidents caused by drunk driving.

---

## 🎯 Objectives

* Detect alcohol consumption before driving.
* Prevent vehicle ignition when alcohol is detected.
* Provide an audible alert using a buzzer.
* Improve road safety using embedded systems.

---

## 🛠️ Components Used

| Component                   | Quantity    |
| --------------------------- | ----------- |
| Arduino UNO                 | 1           |
| MQ3 Alcohol Sensor          | 1           |
| Relay Module                | 1           |
| Buzzer                      | 1           |
| DC Motor (Engine Prototype) | 1           |
| Breadboard                  | 1           |
| Jumper Wires                | As Required |
| Power Supply                | 1           |

---

## ⚙️ Working Principle

1. MQ3 sensor continuously detects alcohol vapors.
2. Arduino reads the sensor values.
3. The sensor values are compared with a predefined threshold.
4. If alcohol concentration exceeds the threshold:

   * Buzzer turns ON.
   * Relay disconnects the engine (DC Motor).
5. If alcohol is not detected:

   * Engine operates normally.

---

## 🔄 System Flow

```text
MQ3 Alcohol Sensor
         ↓
     Arduino UNO
         ↓
 Threshold Comparison
         ↓
   Relay Module
         ↓
   DC Motor (Engine)

      Buzzer Alarm
```

---

## 🚀 Features

* Real-time alcohol detection
* Automatic engine locking
* Buzzer alert system
* Low-cost and easy implementation
* Portable and expandable design

---

## 💡 Applications

* Smart Vehicle Safety Systems
* Commercial Transport Vehicles
* School Buses
* Industrial Vehicles
* Fleet Management Systems

---

## 🔮 Future Scope

* AI-based alcohol prediction system
* Camera-based driver monitoring
* Drowsiness detection using AI
* GPS location tracking
* GSM alert notifications
* Mobile application integration
* Cloud-based monitoring using ESP32

---

## 🧠 AI Integration

Future versions of the system can integrate Artificial Intelligence to:

* Analyze sensor readings more accurately.
* Detect driver drowsiness using computer vision.
* Predict unsafe driving conditions.
* Send emergency alerts with vehicle location.

---

## 📚 Technologies Used

* Arduino UNO
* Arduino IDE
* Embedded C / Arduino C
* MQ3 Alcohol Sensor
* Relay Module
* Buzzer

---

## 📈 Project Outcome

This project helped in understanding:

* Sensor Interfacing
* Embedded Programming
* Relay Control
* Vehicle Safety Systems
* Basic Electronics
* Real-time Monitoring

---

## 👨‍💻 Author

**Yash Gundewadi**

B.Tech - Electronics & Computer Engineering
MIT ADT University
