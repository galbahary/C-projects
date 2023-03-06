cmake_minimum_required(VERSION 3.21)
project(ex2_galbah C)

set(CMAKE_C_STANDARD 11)

add_executable(sort_lines
        main.c
        sort_bus_lines.c
        sort_bus_lines.h
        test_bus_lines.c
        test_bus_lines.h)
