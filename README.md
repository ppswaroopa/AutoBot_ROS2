# Autonomous Turtlebot3 Project with ROS2 in C++

**Goal**: Autonomously navigable Turtlebot3 robot in a Gazebo world using LIDAR and Camera sensors.

**Tasks**

1. Using LIDAR avoid collision.
2. Using Camera follow a line.
3. Use YOLO to detect and respond to traffic signals.

## Build System

* OS : Ubuntu 22.04
* C++ 14
* ROS2 Humble

## Build Instructions

1. Clone the repo to `ros2ws/src'
2. ```
    cd ..
    colcon build --packages-select autobot
    ```
