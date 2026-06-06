# Project Proposal: Deep Reinforcement Learning for Autonomous Mobile Robot Navigation

This repository contains my mini project proposal submission for **Task 4** of the CodeAlpha Robotics & Automation Internship.

## 🎯 Abstract & Objectives
This proposal outlines a shift away from traditional, computationally heavy rule-based navigation algorithms (like A* or Dijkstra's) toward an **End-to-End Deep Reinforcement Learning (DRL)** framework. The target objective is to enable a differential-drive mobile robot to map low-latency sensor streams directly to physical wheel velocities, ensuring zero collisions in unknown, dynamic environments.

### Core Project Milestones:
1. **Simulation Environment:** Setting up an unstructured dynamic workspace using ROS 2 and Gazebo.
2. **AI Control Policy:** Implementing a Proximal Policy Optimization (PPO) agent to manage local path planning.
3. **Reward Function Design:** Optimizing state-space rewards for both path efficiency and collision avoidance.
4. **Sim-to-Real Transfer:** Mitigating the reality gap via domain randomization techniques for physical deployment.

## 🛠️ Proposed Software & Hardware Stack

### Software Infrastructure
- **Operating System:** Ubuntu 22.04 LTS
- **Middleware:** ROS 2 (Humble Hawksbill)
- **Simulation Engine:** Gazebo 11
- **AI Engine:** PyTorch / Stable-Baselines3

### Hardware Prototype Framework
- **Microprocessing Core:** NVIDIA Jetson Orin Nano (8GB)
- **Primary Sensors:** RPLIDAR A1 (360-degree laser scanner) & MPU6050 IMU
- **Actuation System:** Dual Dynamixel XL430 smart servo motors

## 📁 Repository Directory
- `PROJECT PROPOSAL_TASK4.pdf`: The complete 5–6 page technical proposal report.
