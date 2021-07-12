# Using-SLAM-map-to-launch-the-navigation

$ cd ~/catkin_ws/

$ export TURTLEBOT3_MODEL=burger

$ source devel/setup.bash

$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

$ source devel/setup.bash

$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

Click the 2D Pose Estimate button in the RViz menu.

$ source devel/setup.bash

$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
