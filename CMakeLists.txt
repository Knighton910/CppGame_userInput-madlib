cmake_minimum_required(VERSION 3.3)
project(Cpp_Aim)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Cpp_Aim ${SOURCE_FILES})