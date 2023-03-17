cmake_minimum_required(VERSION 3.5)
project(Assignment2)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED YES)

include_directories(Algorithm Common Simulation)

file(GLOB_RECURSE SOURCES "Algorithm/*.cpp" main.cpp)
add_executable(A2 ${SOURCES})
