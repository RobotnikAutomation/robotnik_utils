cmake_minimum_required(VERSION 2.8.3)
project(node_manager)

find_package(catkin REQUIRED COMPONENTS
  rospy
  rosmon_msgs
)
catkin_package()

include_directories(
  ${catkin_INCLUDE_DIRS}
)
