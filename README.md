# Robot Shape Identifier

A robot mapper and controller that is able to identify shaped objects utilising ROS.

This project makes use of git submodules. To retreive the source of the libraries included run `git submodule init` and `git submodule update` from the root directory.

To run the program:
1. run `catkin_make` from the root project directory.
2. using roslaunch run the launch file. i.e. `roslaunch src/main.launch`

__Note__:
The application can be run using an .world file within the src/robot_driver/world file. To change which world file is used, update the 726assignment.launch file in the src directory.
