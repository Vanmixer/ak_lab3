cmake_minimum_required(VERSION 3.16.3)
project(lb3)
add_library(MyProdlib STATIC file.cpp my_lib.cpp my_lib.h)
add_executable(lb3
./file.cpp
./my_lib.cpp
)
