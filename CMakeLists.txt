cmake_minimum_required(VERSION 4.3)
project(DSAP2_fork)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(DSAP2_fork
        datasets.cpp
        main.cpp
        mergesort.cpp
        quicksort.cpp
        tests/test.cpp
        userinterface.cpp
        userinterface.h)
