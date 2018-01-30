cmake_minimum_required(VERSION 3.2)

set(ROS_ROOT $ENV{ROS_ROOT})
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTORCC ON)
  
# Build normally
include(serial.cmake)
message("Building stand alone")
build_serial()

