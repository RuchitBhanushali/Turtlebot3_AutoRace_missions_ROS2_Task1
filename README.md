# Advanced Robotics
ROS 2 Humble implementation of TurtleBot3 Autorace missions (Traffic Light, Intersection, Construction, Tunnel).

## Features
- Lane following and sign detection
- Mission modules: Traffic Light, Intersection, Construction (obstacle avoidance), Tunnel (navigation)
- Auto camera calibration and detection pipelines

## Run
```bash
ros2 launch turtlebot3_gazebo turtlebot3_autorace_2020.launch.py
ros2 launch turtlebot3_autorace_mission mission_construction.launch.py
