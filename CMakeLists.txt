cmake_minimum_required(VERSION 3.12)
project(A3/implementation)

set(CMAKE_CXX_STANDARD 14)

include_directories(.idea)
include_directories(implementation)

add_executable(A3
        implementation/test/testmain.cpp
        implementation/catch/catch.h)
