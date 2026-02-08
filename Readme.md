# Autonomous Tracking Turret

## Overview
This project is a real-time autonomous tracking turret built as a personal and academic robotics project.  
The system is capable of detecting, tracking, and engaging targets using computer vision and closed-loop servo control.

The turret supports both **manual control** and **autonomous vision-based operation**, running on an embedded compute platform with real-time performance constraints.

[![Autonomous Tracking Turret Demo](https://img.youtube.com/vi/QobdRKVzfLg/0.jpg)](https://youtu.be/QobdRKVzfLg)
📹 **Demo Video:** [Watch on YouTube](https://youtu.be/QobdRKVzfLg)

---

## Key Features
- Real-time color-based object detection and tracking
- Closed-loop servo control for smooth pan–tilt motion
- Autonomous target tracking and firing logic
- Manual control mode for testing and calibration
- Low-latency vision-to-actuation pipeline
- Physically built and tested hardware system

---

## Hardware Used
- Embedded compute platform (Jetson-based)
- Pan–tilt servo mechanism (2-DOF)
- PCA9685 servo driver
- USB camera
- External power supply
- Mechanical mounting and custom assembly

---

## Software & Tools
- OpenCV for real-time computer vision
- Embedded C++ / Python for control logic
- Linux-based embedded environment
- PWM-based servo control

---

## Operating Modes

### 1. Manual Control
- Direct user control of turret movement
- Used for calibration, testing, and safety validation

📹 [Watch Manual Control Demo](https://youtube.com/shorts/zR4kt2JjodA)

---

### 2. Autonomous Tracking Mode
- Vision-based target detection
- Automatic pan–tilt adjustment to keep target centered
- Closed-loop control for stable tracking
- End-to-end demonstration of detection, tracking, and actuation

📹 [Watch Autonomous Tracking Demo](https://youtube.com/shorts/aBkurgwH2Bo)

## System Performance
- Real-time tracking with stable servo response
- Optimized control pipeline for low latency

---

## Project Highlights
- Fully physical system (not simulation-based)
- Demonstrates integration of vision, control, and embedded systems
- Awarded **2nd Prize** at a department-level  project competition

---

## Media

### Hardware Setup
Images of the physical setup, mounting, and turret structure are available





