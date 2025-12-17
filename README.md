# 🚗 Autonomous Mobile Robot Using LiDAR (ROS 2)

An autonomous mobile robot capable of **mapping**, **localization**, and **navigation** in unknown environments using **LiDAR sensing** and **ROS 2 Humble**.  
The robot builds a map of its surroundings using SLAM and navigates autonomously to given goals while avoiding obstacles.

---

## 📌 Project Overview

This project focuses on developing a **fully autonomous robot** using a **RPLiDAR A1M8** and **Raspberry Pi 4**, leveraging **ROS 2 Humble** for real-time perception and navigation.  
The robot first scans the environment to generate a map and then uses that map for autonomous path planning and obstacle avoidance.

---

## 🎯 Objectives

- Perform real-time **environment mapping** using LiDAR
- Implement **SLAM** for map generation
- Enable **autonomous navigation** to source and destination points
- Integrate **odometry** using wheel encoders
- Visualize sensor data and robot movement in **RViz**

---

## 🛠️ Hardware Components

- Raspberry Pi 4 (4GB/8GB)
- RPLiDAR A1M8
- BO DC Motors with Magnetic Encoders
- L298N Motor Driver
- Servo Motor (for obstacle detection)
- Robot Chassis (6-wheel drive)
- Power Supply / Battery Pack

---

## 💻 Software Stack

- **Operating System:** Ubuntu 22.04 (ARM)
- **Middleware:** ROS 2 Humble Hawksbill
- **Programming Language:** Python, C++
- **Visualization Tool:** RViz2
- **SLAM Package:** SLAM Toolbox
- **LiDAR Driver:** rplidar_ros
- **Navigation:** Nav2 Stack

---

## ⚙️ System Architecture

