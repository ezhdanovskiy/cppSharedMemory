cmake_minimum_required(VERSION 2.8)
project(SharedMemory)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -pthread")

add_executable(SharedMemory main.cpp)