cmake_minimum_required(VERSION 2.8 FATAL_ERROR)

project(segmentation_framework)

find_package(PCL 1.5 REQUIRED)

include_directories(${PCL_INCLUDE_DIRS})
link_directories(${PCL_LIBRARY_DIRS})
add_definitions(${PCL_DEFINITIONS})

add_executable (segmentation_framework segmentation_framework.cpp)
target_link_libraries (segmentation_framework ${PCL_LIBRARIES})