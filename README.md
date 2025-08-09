# Obstacle Avoiding Robot

## 📌 Overview
An **autonomous obstacle-avoiding robot** built using:
- Arduino Uno
- Ultrasonic sensor for distance detection
- Servo motor for sensor rotation
- DC motors for movement
- L298N motor driver for control

The robot detects obstacles and navigates around them without manual input.

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
1. The ultrasonic sensor scans the surroundings.
2. Measures distances to detect nearby obstacles.
3. If an obstacle is within a set threshold, the robot stops and changes direction.
4. Selects the path with the most clearance.


---

## 📷 Images
You can add images in Markdown like this:
```markdown
![Robot Setup](images/robot_setup.jpg)
![Circuit Diagram](images/circuit_diagram.png)
![Demo](images/demo.gif)
```
Make sure to place your images inside the `images/` folder in your repo.

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
- Initializes the ultrasonic sensor and servo motor.
- Continuously reads distance values.
- Controls motor movement based on detected distances.
- Implements obstacle avoidance logic.

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/Obstacle-Avoiding-Robot.git
```
2. Open `.ino` file in Arduino IDE.
3. Connect the components as shown in the circuit diagram.
4. Upload the code and power the robot.

---

## 🛠️ Tools Used
- Arduino IDE
- Embedded C/C++

---

## ✨ Future Improvements
- Integrate IR sensors for edge detection.
- Add PWM-based speed control.
- Implement Bluetooth remote control.

---

## 📜 License
MIT License
