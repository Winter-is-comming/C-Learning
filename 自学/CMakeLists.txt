cmake_minimum_required(VERSION 3.17)
project(C C)

set(CMAKE_C_STANDARD 11)

link_libraries(m)

add_executable(C main.c)