cmake_minimum_required(VERSION 2.8.4)
project(c_trainning)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.c)
add_executable(c_trainning ${SOURCE_FILES})
