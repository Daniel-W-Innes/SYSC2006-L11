cmake_minimum_required(VERSION 3.10)
project(Lab_11 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(Lab_11
        main.c
        sl_list.c
        sl_list.h)
