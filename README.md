```markdown
# Obstacle Avoiding Robot

## 📌 Overview
An **autonomous obstacle-avoiding robot** built using:
- Arduino Uno
- Ultrasonic sensor for distance detection
- Servo motor for sensor rotation
- DC motors for movement
- L298N motor driver for control

The robot scans for obstacles and navigates around them without manual control.

---

## ⚙️ Components
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- L298N Motor Driver
- 2 × DC Motors with Wheels
- Chassis
- Battery Pack
- Jumper Wires

---

## 🛠️ Working Principle
1. Ultrasonic sensor mounted on servo scans left, front, and right.
2. Measures distances to detect obstacles.
3. If an obstacle is detected within threshold distance, stops and turns.
4. Chooses direction with maximum free space.

---

## 📂 Repository Structure
```
Obstacle-Avoiding-Robot/
├── code/
│   └── obstacle_avoiding_robot.ino
├── images/
│   ├── robot_setup.jpg
│   ├── circuit_diagram.png
│   └── demo.gif
└── README.md
```

---

## 💻 Code Description
- Initializes ultrasonic sensor and servo motor.
- Continuously measures distance.
- Motor driver controls forward, left, and right motion.
- Decision logic avoids collisions.

---

## 🚀 How to Run
1. Clone repository:
   ```bash
   git clone https://github.com/<your-username>/Obstacle-Avoiding-Robot.git
   ```
2. Open `.ino` file in Arduino IDE.
3. Connect circuit as per diagram.
4. Upload code and power the robot.

---

## 📷 Demo
![Robot Setup](images/robot_setup.jpg)
![Circuit Diagram](images/circuit_diagram.png)
![Working Demo](images/demo.gif)

---

## 🛠️ Tools Used
- Arduino IDE
- Embedded C/C++

---

## ✨ Future Improvements
- Add IR sensors for edge detection
- Implement speed control via PWM
- Add Bluetooth manual control

---

## 📜 License
MIT License
```
