#using-gazebo-laser-scan
##Objectives
- Integrate Gazebo Hokuyo laser scan plugin
- View laser scans in Gazebo simulator
- View laser scan data in rviz

##Instructions
- Checkout the source code  
`git checkout https://bitbucket.org/kiranpalla/learn-ros/using-gazebo-laser-scan`  
`cd learn-ros/using-gazebo-laser-scan/src`  
`catkin_create_pkg mybot`  
`cd ..`  
- Build ROS packages  
`catkin_make`  
- Add ROS package to search path (bash shell)  
`source devel/setup.sh`  
- Launch the example  
`roslaunch mybot mybot.launch`
