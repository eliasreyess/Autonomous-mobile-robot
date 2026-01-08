# Autonomous-robot

![Autonomous robot simulation](screenshot_2025_08_10.png)
This project focuses on the design and development of an autonomous mobile robot capable of navigating and operating in dynamic indoor environments. The robot uses LiDAR and ultrasonic (sonar) sensors to perform real-time motion control, obstacle avoidance, and environment mapping, enabling reliable navigation in cluttered spaces.

Control and coordination are handled by a Raspberry Pi running ROS 2, which manages sensor acquisition, low-level control, and localization. Generated maps and sensor data are transmitted to an NVIDIA Jetson module for high-performance processing, including advanced perception and computation-intensive tasks. Development followed a simulation-first workflow within the ROS 2 ecosystem, allowing navigation, mapping, and control algorithms to be validated in simulation before deployment to physical hardware.
