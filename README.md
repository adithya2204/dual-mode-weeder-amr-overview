# AGV Weed Removal – ROS 2 Project Summary

## Overview

This repository provides a high-level overview of a research-focused ROS 2 project aimed at autonomous weed detection and removal in agricultural environments. The project involves a 4-wheeled mobile robot integrated with a 3-DOF manipulator arm, simulated in Gazebo and controlled using ROS 2 Humble. The system is designed to assist farmers by automating weed removal tasks, reducing manual labor, and minimizing the use of herbicides.

## Objective

The primary goal is to develop a multipurpose AGV (Autonomous Ground Vehicle) capable of:
- Navigating autonomously in field environments using SLAM and LiDAR
- Detecting weeds using a vision-based system trained with YOLO
- Removing weeds selectively using a mechanical arm with minimal crop interference

## Core Features

- ✅ **4-Wheeled Differential Drive Base**  
  Enables stable and controlled movement over uneven agricultural terrain in simulation.

- ✅ **3-DOF joint actuator**  
  Designed for flexible weed targeting and removal actions.

- ✅ **ROS 2 & Gazebo Integration**  
  Full simulation of robot behavior, object interactions, and task environments using `gazebo_ros2_control`.

- ✅ **Teleoperation Mode**  
  Manual control of the robot base and manipulator using custom ROS 2 nodes and keyboard input.


## Architecture Summary

- **Platform**: ROS 2 Humble
- **Simulation**: Gazebo, RViz 2
- **Perception**: OpenCV, YOLO (planned/trained model not shared here)
- **Navigation**: LiDAR-based SLAM (planned module)
- **Manipulator Control**: Custom ROS 2 controllers

## Current Status

This project is part of a **project currently under peer review**. To protect the novelty of the contribution, the full implementation — including code, configuration files, URDF/XACROs, and models — has not been published here.

This repository serves as a **summary for recruiters and collaborators** to understand the scope and potential impact of the work.

---

📬 **Request Full Access**  
If you're a **recruiter**, **academic collaborator**, or **research peer** interested in reviewing the full codebase for evaluation or collaboration, please contact me at:

**📧 adithyapothula123@gmail.com**

Access can be granted upon request with appropriate context.

## License

Apache 2.0

---

*Developed as part of a robotics research initiative in agricultural automation, this project explores ROS 2-based intelligent weed removal systems combining autonomy, computer vision, and manipulation in simulation.*
