# Self-Driving Car using Computer Vision and Raspberry Pi

## 📌 Overview

This project presents the development of an autonomous Self-Driving Car system using Computer Vision, Raspberry Pi, OpenCV, and Arduino-based motor control. The primary objective of the project is to enable real-time lane detection, obstacle recognition, traffic sign detection, and autonomous vehicle navigation in a simulated environment.

The system integrates image processing, embedded systems, and intelligent control mechanisms to demonstrate the working principles of autonomous driving technologies used in modern smart vehicles.

---

## 🚀 Key Concepts

### 🔹 Computer Vision for Autonomous Navigation

Computer Vision techniques are used to process real-time camera input and identify important road features such as:

* Lane markings
* Traffic signs
* Obstacles
* Stop indicators

The captured frames are processed using OpenCV to make navigation decisions dynamically.

---

### 🔹 Embedded Autonomous Control

The project combines Raspberry Pi for image processing and Arduino for motor control. The Raspberry Pi performs vision-based decision making, while the Arduino controls wheel movement and steering operations.

---

## 🎯 Objective

The project aims to develop a self-driving robotic vehicle capable of:

* Real-time lane detection
* Autonomous path following
* Traffic sign recognition
* Obstacle detection
* Directional control
* Intelligent motor navigation
* Autonomous turning and stopping mechanisms

---

## ⚙️ Features Implemented

* Lane detection using image thresholding
* Perspective transformation for road view correction
* Edge detection using Canny algorithm
* Histogram-based lane tracking
* Traffic and object detection using Haar Cascade Classifiers
* Real-time camera frame processing
* Motor speed and steering control
* Autonomous navigation commands
* Raspberry Pi and Arduino integration

---

## 🧠 Methodology

* Captured live video frames using Raspberry Pi Camera
* Applied image preprocessing techniques:

  * Grayscale conversion
  * Thresholding
  * Edge detection
  * Perspective transformation
* Detected lane positions using histogram analysis
* Used OpenCV Cascade Classifiers for object and traffic sign recognition
* Generated navigation commands based on lane positions
* Sent directional control signals to Arduino for motor actuation
* Controlled vehicle movement through PWM-based motor control logic

---

## 📊 Results and Analysis

The system successfully demonstrated:

* Real-time lane tracking
* Autonomous steering correction
* Smooth directional movement
* Accurate road path estimation
* Basic obstacle and traffic sign recognition
* Efficient communication between Raspberry Pi and Arduino

The project highlights how computer vision and embedded systems can be combined to build low-cost autonomous driving solutions.

---

## 📚 Applications

This project has applications in:

* Autonomous Vehicles
* Smart Transportation Systems
* Robotics and Automation
* Computer Vision Research
* Intelligent Navigation Systems
* Driver Assistance Technologies

---

## 🛠️ Tech Stack

* Programming Languages: C++, Arduino C
* Platforms: Raspberry Pi, Arduino
* Libraries: OpenCV, WiringPi, RaspiCam
* Concepts: Computer Vision, Embedded Systems, Robotics

---

## 📌 Future Work

* Deep learning-based object detection
* GPS-assisted autonomous navigation
* Real-time traffic signal interpretation
* Obstacle avoidance using ultrasonic sensors
* Integration with IoT-based monitoring systems
* Advanced path planning algorithms
* Autonomous parking system implementation

---

## ⭐ Conclusion

This project demonstrates the implementation of a vision-based Self-Driving Car system using Raspberry Pi and Arduino. By integrating computer vision algorithms with embedded motor control systems, the project successfully performs autonomous lane tracking, navigation, and object detection. The work provides practical exposure to robotics, intelligent transportation systems, and real-time embedded AI applications, making it a strong foundation for future autonomous vehicle research and development.
