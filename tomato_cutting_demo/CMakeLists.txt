cmake_minimum_required(VERSION 2.8.3)
project(tomato_cutting_demo)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
   INCLUDE_DIRS
   LIBRARIES ${PROJECT_NAME}
   CATKIN_DEPENDS
   DEPENDS
)
