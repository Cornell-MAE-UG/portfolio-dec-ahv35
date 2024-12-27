---
layout: project
title: Tracking a Car using a Drone with a Camera
description: Robot Perception Final Project
technologies: [Matlab, python]
image: "assets/images/drone_track_car.png"
pdf_local: "/assets/pdfs/Final_Project_Robot_Perception.pdf"
---

This project simulates a drone equipped with a pan-tilt camera tracks a moving car. The quadcopter, modeled as a rigid-body system, uses a Linear Quadratic Regulator (LQR) for optimal control to maintain the car centered within the camera’s field of view. The car’s dynamics are based on the Ackerman steering model, used in the motion planner which predicts the car’s future positions, generating a trajectory for the drone to intercept it while adjusting camera angles to maintain visual alignment. The simulation evaluates the system’s performance under three car paths: linear, circular, and spiral. Results demonstrate the drone’s capability to dynamically track the car using the LQR-based control strategy.

{% pdf {{ page.pdf_local }} %}
