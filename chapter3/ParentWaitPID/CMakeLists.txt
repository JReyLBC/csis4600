cmake_minimum_required(VERSION 3.3)
project(ParentWaitPID)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

set(SOURCE_FILES main.c)
add_executable(ParentWaitPID ${SOURCE_FILES})