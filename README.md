# RoboND-Home-Service-Robot

This is the final project of Udacity Robotics Nanodegree. In this project, a small home service robot is simulated in a Gazebo environment.

# Summary of Tasks
1. Design a simple environment with the Building Editor in Gazebo.
2. Teleoperate your robot and manually test SLAM.
3. Create a wall_follower node that autonomously drives your robot to map your environment.
4. Use the ROS navigation stack and manually commands your robot using the 2D Nav Goal arrow in rviz to move to 2 different desired positions and orientations.
5. Write a pick_objects node that commands your robot to move to the desired pickup and drop off zones.
6. Write an add_markers node that subscribes to your robot odometry, keeps track of your robot pose, and publishes markers to rviz.

# How to use this repository
first change to the workspace directory
``` bash
$ cd ~/catkin_ws
```
Testing SLAM
``` bash
$ ./src/ShellScripts/test_slam.sh
```
Testing Navigation
``` bash
$ ./src/ShellScripts/test_navigation.sh
```
Saving SLAM Map
``` bash
./src/ShellScripts/save_map.sh
```
Pick_objects
``` bash
$ ./src/ShellScripts/pick_objects.sh
```
Add Markers
``` bash
$ ./src/ShellScripts/add_marker.sh
```
Home Service
``` bash
$ ./src/ShellScripts/home_service.sh
```
