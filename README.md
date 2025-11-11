# 🚗 Obstacle-Detection-Robot
 
## 📌 Overview
This project demonstrates an autonomous **Obstacle Detection & Avoidance Robot** using Arduino UNO.  
The robot uses an ultrasonic sensor (HC-SR04) to detect obstacles in its path and automatically navigates by controlling two DC motors through an L298N motor driver. When an obstacle is detected within the defined range, the robot stops, reverses, and turns to avoid collision — enabling fully autonomous movement.

---

## ✨ Key Features
- ✅ Real-time distance measurement using Ultrasonic Sensor (HC-SR04)
- ✅ Autonomous movement and obstacle avoidance logic
- ✅ Motor control using L298N motor driver
- ✅ TinkerCAD simulation + working video demo included
- ✅ Cost-efficient and ideal for learning embedded systems & robotics

---

## 🔧 Hardware Components

|         Component         |   Specification / Purpose   |
|---------------------------|-----------------------------|
|        Arduino UNO        | Main microcontroller board  |
| Ultrasonic Sensor(HC-SR04)| Distance measurement        |
|     L298N Motor Driver    | Controls DC motors movement |
|      DC Motors (2x)       | Drives the robot            |
|   Battery (9V / Li-ion)   | Power source                |
|   Jumper wires, chassis   | Support & connections       |


## 🛠 Circuit Simulation (TinkerCAD)

🧩 View or simulate the circuit here:

🔗 **TinkerCAD Simulation Link:**  
https://www.tinkercad.com/things/5MSPJWvNYjH-surprising-kasi

> Includes full circuit wiring of Arduino, L298N, ultrasonic sensor, and power connections.

---

## 🎥 Demo Video

▶️ **Watch the working robot in action:**  
https://youtu.be/YourVideoLink

---

## 🧠 Working Logic

1. Ultrasonic sensor sends a signal and measures the echo time.
3. Arduino calculates the distance using the speed of sound.
4. If an obstacle is detected within 20 cm:
   - Robot stops
   - Moves backward
   - Turns right and continues moving
5. If no obstacle detected:
   - Moves forward continuously

---

## 📁 Source Code

The complete Arduino code is provided in the repository:

📄 `Obstacle-Detection-Robot.cpp`

---

## 📷 Files Included
- ✅ Arduino source code `.cpp`
- ✅ TinkerCAD simulation file `.f3z`
- ✅ Circuit diagram (exported from TinkerCAD)
- ✅ Working video link



