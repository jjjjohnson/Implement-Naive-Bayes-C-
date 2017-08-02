cmake_minimum_required(VERSION 3.7)
project(prediction2)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        main.cpp
        classifier.cpp
        classifier.h)
add_executable(prediction2 ${SOURCE_FILES})