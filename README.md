# Ummannd_Car_Project

## About The Project 
This is a Gazebo simulation which is a vehicle moves in the room, developer can add more function in this package.  

## Built With
* Ubuntu 20.04
* ROS2 foxy
* Gazebo

## Getting Started
### Configuration

1. Put this package into your ros2 workspace and build 
``` shell
colcon build --symlink-install --packages-select car_test
```
2. Start simulation
``` shell
ros2 launch care_world.launch.py
```

## Usage

* Vehicle
![image](https://user-images.githubusercontent.com/98295556/193447710-9597a2ec-7d9e-443b-a3d4-129ad4f0ba4d.png)

* Moving
