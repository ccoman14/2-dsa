cmake_minimum_required(VERSION 3.15)
project(E1 C)

set(CMAKE_C_STANDARD 99)

add_executable(E1 main.c sll.h sll.c input.h input.c functions.h functions.c)