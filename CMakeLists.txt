cmake_minimum_required(VERSION 3.1)
set(CMAKE_CXX_STANDARD 11)
project(hole_fixer)

include_directories(libigl/ libigl/eigen/)
add_executable(hole_fixer main.cpp)
