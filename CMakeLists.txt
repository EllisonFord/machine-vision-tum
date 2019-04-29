cmake_minimum_required(VERSION 2.8.3)
project(machine-vision-tum)

add_compile_options(-std=c++17)

## SPEECH
add_executable(main src/main.cpp)
