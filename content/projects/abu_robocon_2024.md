---
title: "ABU Robocon - 2024, Vietnam"
description: "an Asian-Oceanian college robot competition, founded in 2002 by Asia-Pacific Broadcasting Union"
image: "/images/abu_robocon/2024/mr_closeup.jpeg"
weight: 1
date: 2026-01-29
github_url: "https://github.com/tyro-apil/weather-dashboard"
tech_stack: ["ROS2", "Python", "OpenCV", "YOLOv8"]
tags: ["Robocon", "Computer Vision", "camera", "perception"]
---

## Official Competition Theme

{{< youtube zavE1DzyH6Q >}}

## [Details about the Event](https://robotics.pcampus.edu.np/robocon/2024/)

## About Project

Our team from [Robotics Club Pulchowk](https://robotics.pcampus.edu.np/) represented our nation **Nepal** in the competition by making *a manual robot* and *an automatic robot* based on the team and provided criteria. We worked for about **10 months** from Oct. 2023 - Jul. 2024 and won **Tokyo Electron Award**.

## Contributions Made

I designed the perception pipeline for the autonomous robot using depth and monocular cameras. I fine-tuned YOLOv8 model for object detection and analysis of game field. Based on the perceived state of the environment, the robot needed to perform its tasks -- quickly pick up the team-colored ball **(Task-1)** and quickly store the picked ball into the optimal storage vessel **(Task-2)**.

{{< image_pair
    image1="/images/abu_robocon/2024/obj_det.jpg"
    alt1="Area 3 - Front Camera Feed (OAKD Pro-W Depth Camera)"
    caption1="Area 3 - Front Camera Feed (OAKD Pro-W Depth Camera)"
    image2="/images/abu_robocon/2024/rviz2_1.png"
    alt2="Robot's Perception of Area 3"
    caption2="Robot's Perception of Area 3"
    gap="2rem"
>}}

{{< image_pair
    image1="/images/abu_robocon/2024/silo_state.jpg"
    alt1="Area 3 - Back Camera Feed (Picamera v3 Wide)"
    caption1="Area 3 - Back Camera Feed (Picamera v3 Wide)"
    image2="/images/abu_robocon/2024/rviz2_2.png"
    alt2="Robot's Perception of Storage Vessels"
    caption2="Robot's Perception of Storage Vessels"
    gap="2rem"
>}}

## Appendix

### [Source Code -- Computer Vision Part I](https://github.com/tyro-apil/oakd_ros)

### [Source Code -- Computer Vision Part II](https://github.com/tyro-apil/ar_storage)
