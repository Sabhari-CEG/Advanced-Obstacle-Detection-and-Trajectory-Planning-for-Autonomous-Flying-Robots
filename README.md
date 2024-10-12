# Advanced-Obstacle-Detection-and-Trajectory-Planning-for-Autonomous-Flying-Robots
This project demonstrates a sophisticated AI-driven system for autonomous flying robots, featuring real-time obstacle detection, dynamic trajectory planning, and adaptive speed control. It enhances safety and efficiency in navigation, showcasing advanced applications in autonomous driving, robotics, and computer vision.

## Overview

This project showcases a cutting-edge solution for autonomous navigation in dynamic environments, leveraging advanced AI and computer vision technologies. Our system is designed to enhance the safety and efficiency of flying robots by integrating real-time obstacle detection, collision avoidance, and trajectory planning.

## Robot Assumptions

Our autonomous flying robot is designed with the following capabilities:

- **Flying Capabilities**: The robot can fly up and down, allowing it to navigate through three-dimensional spaces effectively.
- **Directional Movement**: It can move in all four horizontal directions (forward, backward, left, right), providing comprehensive maneuverability.
- **Adaptive Speed Control**: The robot adjusts its speed dynamically based on proximity to obstacles, ensuring safe navigation.

## Features

- **Real-Time Obstacle Detection**: Utilizes state-of-the-art machine learning algorithms to identify and classify obstacles using sensor data.
- **Dynamic Trajectory Planning**: Employs predictive modeling to simulate future paths, allowing proactive course adjustments.
- **Scalable AI Integration**: Built on a scalable AI framework adaptable for various autonomous systems.

- ## SYNTHIA Dataset

I utilized the [SYNTHIA dataset](https://www.kaggle.com/datasets/tzokas027/synthia) for training and testing my model. This dataset is known for its synthetic images that provide detailed annotations for various urban scenes.

### Structure

The SYNTHIA dataset is organized into several folders, each containing different types of data:

- **RGB**: Contains color images that simulate real-world urban environments.
- **Depth**: Provides depth maps corresponding to each RGB image, useful for distance estimation.
- **GT (Ground Truth)**: Includes semantic segmentation masks that label different objects within the scene.

### Sample Image

A typical sample from the SYNTHIA dataset includes an RGB image paired with its corresponding depth map and ground truth segmentation. This comprehensive data allows for robust training of models in tasks such as object detection and depth estimation.

![Sample Image](0000028.png) <!-- Add a sample image from the dataset here -->

