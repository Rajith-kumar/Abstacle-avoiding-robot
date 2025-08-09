# Abstacle-avoiding-robot


```markdown
# Obstacle Avoiding Robot

## 📌 Overview
This project implements an **autonomous obstacle-avoiding robot** using:
- **Arduino Uno**
- **Ultrasonic sensor** for distance measurement
- **Servo motor** for sensor rotation
- **DC motors** for movement
- **Motor driver (L298N)** for motor control

The robot detects obstacles in its path and changes direction accordingly.

---

## ⚙️ Components Used
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90)
- L298N Motor Driver
- 2 × DC Motors
- Wheels & Chassis
- Battery Pack (9V or Li-ion)
- Jumper Wires

---

## 🛠️ Working Principle
1. The ultrasonic sensor, mounted on a servo motor, scans the surroundings.
2. Distance to obstacles is calculated.
3. If an obstacle is detected within a set range, the robot stops and turns.
4. Based on readings, the robot chooses the path with more free space.

---

## 📂 Repository Structure
```
Obstacle-Avoiding-Robot/
│
├── code/
│   └── obstacle_avoiding_robot.ino   # Arduino code
│
├── images/
│   └── robot_setup.jpg              # Pictures of the robot
│
├── README.md                         # Project documentation
└── circuit_diagram.png               # Circuit wiring diagram
```

---

## 💻 Code Description
The Arduino sketch:
- Initializes ultrasonic sensor and servo.
- Continuously measures distances.
- Controls motor direction via L298N driver.
- Implements decision logic for movement.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Obstacle-Avoiding-Robot.git
   ```
2. Open `obstacle_avoiding_robot.ino` in Arduino IDE.
3. Upload the code to Arduino Uno.
4. Connect all components as per `circuit_diagram.png`.
5. Power up and watch the robot navigate!

---

## 📷 Demo
*(Insert images and videos here)*

---

## 🛠️ Tools Used
- Arduino IDE
- Embedded C/C++
- Ultrasonic Sensor
- Servo Motor & DC Motors

---

## ✨ Future Improvements
- Add IR sensors for edge detection.
- Implement speed control using PWM.
- Add Bluetooth module for manual override.

---

## 📜 License
This project is licensed under the MIT License.
```

For GitHub, you should keep:
- `README.md` (above content)
- `code/` folder with `.ino` file
- `images/` folder with photos
- Circuit diagram image
- License file

I can also prepare the **Arduino `.ino` code** structure if you haven’t finalized it yet.
