# RTAB-Map
Real-Time Appearance-Based Mapping for robot SLAM localization implemented with ROS.


# Install and Run

Dependenties packages must be installed in your computer, if your using Lubuntu you can install as:
```sudo apt-get install ros-kinetic-rtabmap-ros´´´
for other installation system please check oficial (instructions)[https://github.com/introlab/rtabmap_ros#rtabmap_ros]

For running the code you need to build the project as :
``` cd <project_root_dir>: 
    ./catkin_make
    ./source devel/setup.bash
    ./roslaunch my_robot world.launch
```
# Robot and World
Robot sensors:
-Kinect camera for RTAB-Map.

# Packages
used packages:
1. [RTAB-Map](http://wiki.ros.org/rtabmap_ros)
⋅⋅⋅2D Laser sensor_msgs/LaserScan messages
⋅⋅⋅Odometry sensors, providing nav_msgs/Odometry messages 
⋅⋅⋅3D Camera, compatible with openni_launch, openni2_launch or freenect_launch ROS packages      

# Citations
1. Udacity Robotics Software Engineer Nanodegree Program
