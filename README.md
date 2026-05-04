# 🤖 LLM-Based Mobile Robot Path Planning

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![ROS](https://img.shields.io/badge/ROS-Noetic-22314e)](https://wiki.ros.org/noetic)
[![Gazebo](https://img.shields.io/badge/Gazebo-11.x-orange)](https://gazebosim.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview

This project introduces a novel framework that embeds **Large Language Models (LLMs)** into mobile robot navigation systems. The framework translates high-level natural language commands into actionable, dynamic waypoints, enabling robots to navigate and re-plan in complex environments without retraining.

> The proposed approach integrates real-time obstacle avoidance and voice-command interaction, allowing humans to communicate with robots intuitively. Experimental results across multiple environments demonstrate that our Llama3.1-based framework significantly improves path planning efficiency, waypoint generation success rates, and collision avoidance[reference:0].

![Simulation Demo](assets/demo.gif) 
*Replace `assets/demo.gif` with an actual animation of the robot navigating a corridor.*


### Simulation - Gazebo + Rviz

Below are simulation snapshots from our corridor environments:

| 🗺️ Corridor World | 🧠 Rviz Visualization |
|---|---|
| *Gazebo simulation of TurtleBot3 navigating a corridor environment.* | *Rviz showing waypoints, robot model, and TF frames.* |
| *Replace with actual simulation image* | *Replace with actual Rviz screenshot* |

> Refer to the published article for full quantitative results and environment details [here](https://www.sciencedirect.com/science/article/abs/pii/S0957417425012229)[reference:1].

## 🚀 Key Features

- **🧠 LLM-Powered Planning**: Uses LLMs (Llama3.1, Qwen2.5, Mathstral) for dynamic waypoint generation[reference:2]
- **🗣️ Voice Commands**: Integrated Google Speech Recognition for intuitive human-robot interaction[reference:3]
- **🔄 Realtime Replanning**: Dynamically adjusts paths in response to obstacles[reference:4]
- **🎮 Simulation Ready**: Full ROS + Gazebo integration with TurtleBot3
- **📊 Multi-Model Testing**: Compare performance across different LLM models

## 📁 Repository Structure
