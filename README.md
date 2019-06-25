# Turtlebot3_trash_sweep

## Test_Video
[![Video Label](http://img.youtube.com/vi/A5QSnYqkHds/0.jpg)](https://youtu.be/A5QSnYqkHds?t=0s)

https://youtu.be/A5QSnYqkHds

## How to launch
Turtlebot

ssh pi@192.168.0.125

export TURTLEBOT3_MODEL=waffle_pi

ROS_NAMESPACE=om_with_tb3 roslaunch turtlebot3_bringup turtlebot3_robot.launch multi_robot_name:=om_with_tb3 set_lidar_frame_id:=om_with_tb3/base_scan



PC

roscore

export TURTLEBOT3_MODEL=waffle_pi

ROS_NAMESPACE=om_with_tb3 roslaunch open_manipulator_with_tb3_tools om_with_tb3_robot.launch

export TURTLEBOT3_MODEL=waffle_pi

roslaunch open_manipulator_with_tb3_tools rooms.launch

export TURTLEBOT3_MODEL=waffle_pi

roslaunch open_manipulator_with_tb3_tools task_controller.launch 
