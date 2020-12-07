cmake_minimum_required(VERSION 3.17)
project(L_M_example)

set(CMAKE_CXX_STANDARD 14)
find_package(Eigen3 REQUIRED)
include_directories(${EIGEN3_INCLUDE_DIR})

add_executable(L_M_example main.cpp)