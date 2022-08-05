cmake_minimum_required(VERSION 3.21)
project(HomeWork31_2)

set(CMAKE_CXX_STANDARD 14)

add_executable(HomeWork31_2 src/main.cpp include/igraph.h include/listgraph.h include/matrixgraph.h src/listgraph.cpp src/matrixgraph.cpp)
