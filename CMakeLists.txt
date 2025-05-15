cmake_minimum_required(VERSION 3.13)
project(libpcb)

set(CMAKE_CXX_STANDARD 20)

add_library(libpcb STATIC libpcb.cpp)

add_executable(testrun testrun.cpp)
