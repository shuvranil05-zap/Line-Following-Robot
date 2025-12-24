# Line Following Robot using Arduino (IR Sensors + PID)

A modular Line Following Robot built using Arduino Uno, IR sensors, L298N motor driver, and PID control to achieve smooth, accurate, and stable navigation along a predefined path.

This project was developed as a first hands-on robotics project, focusing on embedded systems fundamentals, sensor calibration, motor control, and control algorithms.

## 📌 Project Overview

This project involves the design and implementation of a Line Following Robot that detects a black line on a white surface using active-LOW IR sensors and dynamically adjusts motor speed using a PID control algorithm.

Key objectives of the project include:

* Accurate black/white line detection
* Stable motor control using L298N motor driver
* Smooth turning and correction using PID control
* Reliable performance under edge cases and disturbances

## 🧠 Working Principle

* IR sensors detect surface contrast:
  * BLACK → LOW
  * WHITE → HIGH
* Sensor readings are processed to calculate positional error
* PID controller computes correction values
* Motor speeds are adjusted to keep the robot centered on the line

## 🔧 Hardware Components
 
* Arduino Uno ×1
* IR Obstacle Avoidance Sensor Module ×2
* L298N Motor Driver ×1
* DC Motors (100 RPM) ×2
* BO Wheels ×2
* Metal Ball Caster Wheel ×1
* Li-ion Battery (3.7V) ×2
* Breadboard ×1
* Jumper Wires
