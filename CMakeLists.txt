cmake_minimum_required(VERSION 2.8)

project(os-kidshell)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS_DEBUG "-fsanitize=address,undefined")
set(CMAKE_CXX_FLAGS_RELEASE "-O3")

add_executable(os-kidshell os-kidshell.cpp)
