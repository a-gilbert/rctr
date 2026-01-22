cmake_minimum_required(VERSION 3.31.10)
project(rctr)

message(STATUS "cmake source dir: ${CMAKE_SOURCE_DIR}")
add_executable(hello ../../src/hello.cpp)
