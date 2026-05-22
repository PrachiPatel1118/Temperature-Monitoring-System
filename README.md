# 🌡️ Temperature Monitoring & Alert System

## 📌 About The Project
This is an embedded systems project built using Arduino Uno.
It reads temperature and humidity using a DHT11 sensor,
displays the values on a 16x2 LCD screen, and triggers
a buzzer alert when temperature goes above a set limit.

## 🎯 Problem It Solves
In industries, server rooms, or medical storage — 
temperature must stay in safe range. This system 
automatically alerts when temperature crosses the 
danger level, preventing damage.

## ⚙️ Components Used
| Component | Quantity |
|---|---|
| Arduino Uno | 1 |
| DHT11 Sensor | 1 |
| 16x2 LCD Display | 1 |
| Buzzer | 1 |
| Resistors & Wires | As needed |

## 🔧 How It Works
1. DHT11 sensor reads temperature every 2 seconds
2. Values are displayed on LCD screen in real time
3. If temperature exceeds 35°C, buzzer triggers alert
4. System resets automatically when temperature is normal

## 💻 Software Used
- Arduino IDE
- Tinkercad (for simulation)

## 📷 Circuit Diagram
![Circuit Diagram](images/circuit.png)

## 🖥️ Simulation Screenshot
![Simulation](images/simulation.png)

## 📂 Project Structure
Temperature-Monitoring-System/
│
├── code/
│   └── temperature_monitor.ino
│
├── images/
│   ├── circuit.png
│   └── simulation.png
│
└── README.md

## 🧠 What I Learned
- How to interface DHT11 sensor with Arduino
- Displaying data on LCD using I2C
- Writing conditional alerts in embedded C
- Circuit simulation using Tinkercad

## 👤 Author
Prachi Patel
3rd Year Electronics Engineering
MSU

## 📅 Date
May 2026
