cmake_minimum_required(VERSION 3.6)
project(odd_even_transposition_sort)

#set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_COMPILER "/usr/bin/mpic++")

add_executable(odd_even_transposition_sort main.cpp)

include_directories("/usr/include/mpi/")