# learn-ros

# ROS (Robot Operating System) Learning Series
The purpose of this repository is to share ROS knowledge, concepts using simple stand-alone practical examples. Every example usually has an associated explainer/instruction video.

## Playing with Examples!
Every example works stand-alone. You can download the entire repository or a specific example.

- To starting working with an example, first, check it out  
`git checkout https://bitbucket.org/kiranpalla/learn-ros/<example>`  
- Initialize workspace and compile ROS packages  
`cd learn-ros/<example>/src`  
`catkin_create_pkg mybot`  
`cd ..`  
`catkin_make`  
- Add ROS package to search path (bash shell)
`source devel/setup.sh`
- Launch the example  
`roslaunch mybot mybot.launch`

## List of Examples
Directory | Description | Video Link
:---------|:------------|:----------
using-gazebo-laser-scan|Integrate Gazebo Hokuyo laser plugin with simulated robot|TBD

## Repository Contributors
Name | Profile
:----|:-------
Kiran Palla|[kiranpalla.com](https://kiranpalla.com)

## Credits
To all the developers of ROS, Gazebo simulator, Ubuntu and to other open-source applications.







