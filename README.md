# 🦾 Autonomous Mobile Robot Navigation - Pioneer P3-DX

This repository showcases the implementation of **three key behaviors** **waypoint following**, **target tracking**, and **obstacle avoidance** on the **Pioneer P3-DX** robot platform using **Java**, **MobileSim**, **OpenCV**, and other related tools.

## 📌 Overview

This project was developed as part of the *Mobile Robotics* module at the University of Salford. The goal was to enhance the autonomy, adaptability, and safety of a mobile robot operating in a dynamic environment by integrating:

- **Odometry-based Waypoint Navigation**
- **Color Blob-based Target Tracking**
- **Ultrasonic Sensor-based Obstacle Avoidance**

## 🧠 Behaviors Implemented

### 1. 🚦 Waypoint Following (Odometry Model)
- Uses differential drive kinematics.
- Angular and linear transitions to align and move toward GPS-defined waypoints.
- Implemented with real-time feedback using encoder data.

### 2. 🎯 Target Tracking
- Uses OpenCV color blob detection.
- Dynamically adjusts robot heading and speed to follow targets.
- Vision-based tracking with real-time blob center detection.

### 3. 🛑 Obstacle Avoidance
- Utilizes Pioneer P3-DX's 8 ultrasonic sensors.
- Implements collision, avoidance, and untrapping vectors.
- Avoids static and dynamic obstacles using simple reactive logic.

## 🧪 Experimental Results

### ✅ Odometry Phase
- Mean Distance: **322.9 mm**
- Mean Time: **185.4 sec**
- Correlation Coefficient: **0.921**

### ✅ Tracking Phase
- Mean Distance: **198.5 mm**
- Mean Time: **120.94 sec**
- Correlation Coefficient: **-0.2367**

## 💻 Software Stack

- **Java** (via JDK 7)
- **IntelliJ IDEA** (Development Environment)
- **MobileSim** (Simulation)
- **OpenCV** (Color tracking & computer vision)
- **ARIA & Mapper3** (Robot middleware and visualisation)
- **FTDI Drivers** (USB communication with robot)

## 📂 Project Structure

- `/docs`: Contains report and documentation.
- `/code`: Source code implementing navigation behaviors.
- `/media`: Screenshots, graphs, and charts from experiments.
- `/data`: Raw experiment results and waypoint tables.

## 🔗 Code Access

👉 [Click here to access the full code via Google Drive](https://drive.google.com/drive/folders/1b2eC8GPXccAh-HmDpnXM278fJ_h-qrz_?usp=sharing)

## 📖 Citation

Oke Iyanuoluwa Enoch, *Autonomous Mobile Robot Navigation: Implementing Three Key Behaviors*, University of Salford, 2024.

---

> **Contact**  
> 📧 oke.iyanuoluwa12@gmail.com  

