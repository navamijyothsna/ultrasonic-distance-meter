# 📌 Ultrasonic Distance Meter (Arduino)

## 📖 Project Overview
This project measures the distance of an object using an HC-SR04 ultrasonic sensor and displays the result on the Arduino Serial Monitor. It is a beginner-friendly robotics project that demonstrates sensor interfacing and distance calculation.

---

## ⚙️ Components Used
- Arduino Uno  
- HC-SR04 Ultrasonic Sensor  
- Jumper wires  
- Breadboard (optional)

---

## 🔌 Circuit Connections

<img width="600" height="400" alt="circuit" src="https://github.com/user-attachments/assets/f6a1739f-f6e1-4ece-81b6-137b83c186b0" />


---

## 🧠 Working Principle
The ultrasonic sensor sends a sound pulse using the TRIG pin.  
The pulse reflects back from an object and is received by the ECHO pin.

The distance is calculated using:

Distance = (Time × Speed of Sound) / 2

Speed of sound = 0.0343 cm/µs

---

## ▶️ How to Run
1. Connect the circuit as per wiring table
2. Upload the code to Arduino Uno
3. Open Serial Monitor (9600 baud)
4.View real-time distance readings

---

## 📊 Sample Output
Distance: 25.4 cm
Distance: 18.2 cm
Distance: 12.7 cm

---

## 🚀 Future Improvements
- Add LED indicators (Green/Yellow/Red based on distance)
- Add buzzer alert system
- Add LCD display for standalone output
- Convert into obstacle detection robot
