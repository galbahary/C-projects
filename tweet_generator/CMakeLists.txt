cmake_minimum_required(VERSION 3.21)
project(ex3a_galbah C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(ex3a_galbah
        linked_list.c
        linked_list.h
        markov_chain.h
        tweets_generator.c
        markov_chain.c)
