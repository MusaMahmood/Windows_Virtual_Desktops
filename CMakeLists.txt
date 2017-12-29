cmake_minimum_required(VERSION 3.9)
project(virgo)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(virgo
        virgo.c)
