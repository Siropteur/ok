cmake_minimum_required(VERSION 3.19)
project(ok)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ok
        README.md
        Test.c)
