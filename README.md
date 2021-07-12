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

![التقاط5](https://user-images.githubusercontent.com/86454996/125332687-0378bd80-e352-11eb-9e26-f027099ffd48.PNG)
![ال](https://user-images.githubusercontent.com/86454996/125332699-070c4480-e352-11eb-8611-5647da5597de.PNG)
