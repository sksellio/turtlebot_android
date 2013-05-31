cmake_minimum_required(VERSION 2.8.3)
project(turtlebot_android)

find_package(catkin REQUIRED rosjava_tools)

catkin_rosjava_setup(debug)

catkin_package()

