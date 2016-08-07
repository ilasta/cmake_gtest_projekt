cmake_minimum_required(VERSION 3.5)
project(v_box_button)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(v_box_button ${SOURCE_FILES})