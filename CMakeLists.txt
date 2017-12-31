cmake_minimum_required(VERSION 3.9)
project(virgo)

set(CMAKE_CXX_STANDARD 11)

include_directories(.
        C://msys32//mingw32//i686-w64-mingw32//include)

add_executable(virgo
        virgo.c)
