cmake_minimum_required(VERSION 2.8.3)
project(kaqi_bringup)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  kaqi_description
  kaqi_driver
  kaqi_msgs
  kaqi_teleop
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES kaqi_bringup
#  CATKIN_DEPENDS kaqi_description kaqi_driver kaqi_msgs kaqi_teleop
#  DEPENDS system_lib
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
