# 🚗💡 Autonomous Car Speed Reduction & Obstacle Detection Using IoT

> 🔧 An IoT-based smart vehicle system that detects obstacles and automatically reduces speed to avoid collisions.  
🎓 UG Mini Project – Developed using Arduino UNO & Ultrasonic Sensor.

---

## 🧠 Abstract

In developing countries, 🚧 road accidents are a major cause of death. This project introduces a prototype for an **autonomous vehicle** that uses **ultrasonic sensors** to detect obstacles and control speed automatically using an Arduino UNO.

The aim is to enhance driver safety, reduce manual intervention, and support smart transport development. 🚘

---

## 🎯 Objective

- 📡 Detect obstacles using an ultrasonic sensor  
- ⛔ Reduce motor speed automatically when an obstacle is near  
- 🔁 Reroute using servo motor (left/right) to avoid collisions  
- 🖥️ Display distance info and alerts using an LCD  

---

## 🛠️ Components Used

| 🔢 No. | 🔧 Component              | 📄 Description                                  |
|--------|---------------------------|--------------------------------------------------|
| 1️⃣     | Arduino UNO               | Main microcontroller (ATmega328P)               |
| 2️⃣     | Ultrasonic Sensor HC-SR04 | For measuring distance from obstacles           |
| 3️⃣     | H-Bridge L293D            | Motor driver for speed control                  |
| 4️⃣     | Servo Motor               | For left/right scanning                         |
| 5️⃣     | DC Motor                  | Moves the car prototype                         |
| 6️⃣     | LCD Display               | Shows real-time alerts/instructions             |
| 7️⃣     | Breadboard & Jump Wires   | Used for prototyping and connections            |
| 8️⃣     | AA Battery (4x)           | Power source for the robot                      |

---

## 💻 Software & Simulation Environment

- 🧠 **Arduino IDE** – Writing & uploading code to board  
- 🧪 **TinkerCAD Circuits** – Simulation of electronic components

---

## 📷 Output Results

Here are some real-time results from the prototype's functioning:

| 🚘 Moving | 📍Obstacle Detected | ⏬ Speed Reduced |

| ![Result](result_iot_proj/result_1.jpg) | ![Result](result_iot_proj/result_2.jpg) |

---

## 🔁 Methodology

### 🔄 Control Flow

1. 🏁 Robot starts and moves forward  
2. 📏 Ultrasonic sensor continuously measures the distance  
3. ⚠️ If the distance < threshold:
   - LCD shows **warning**
   - Speed is reduced gradually  
   - Robot changes direction using servo motor
4. 🔁 Repeats the process infinitely until destination is reached
![Circuit Diagram](control_flow.jpg)
---

## 📐 Circuit Diagram

![Circuit Diagram](circuit_diagram.jpg)
