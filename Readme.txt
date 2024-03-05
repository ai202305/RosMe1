ROS Noetic, Gazebo and LOAM is installed on Ubuntu 20.04

# Linux Username: zhong
# Linux Password : pcg@110203

# Check ROS version

$rosversion -d

# Execute Gazebo

$gazebo

# Execute SLAM

$cd ~/catkin_ws

$source ~/catkin_ws/devel/setup.bash

$roslaunch loam_velodyne loam_velodyne.launch