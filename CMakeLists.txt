cmake_minimum_required(VERSION 3.20)
project(AVL_Tree_master C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(AVL_Tree_master
        bintree.c
        bintree.h
        main.c)
