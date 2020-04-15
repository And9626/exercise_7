# exercise_7
This exercise provides the tf tree of a kuka iiwa robot used as a pan_tilt robot.

In order to test this code follow the following step after you had compile the folder

1- roscore
2- launch coppeliasim, load the scene that you find in the repository and run
3- launch the exercise_7.launch
4- use "rosrun tf tf_echo base_link link_1" to evaluate the translation and rotation between the base_link and the pan_link which we control in the pan_controller.cpp
