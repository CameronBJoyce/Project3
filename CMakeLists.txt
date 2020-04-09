cmake_minimum_required(VERSION 3.15)
project(Project03 C)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")

add_executable(Project03 besttrade.c besttrade.h main.c)