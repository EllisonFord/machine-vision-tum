cmake_minimum_required(VERSION 3.10)
project(machine-vision-tum)

add_compile_options(-std=c++17)

#find_package(OpenCV REQUIRED)
#include_directories(${OpenCV_INCLUDE_DIRS})

include_directories(include ${INCLUDE_DIRS})

## MAIN
add_executable(main src/main.cpp)
#target_link_libraries(main ${OpenCV_LIBS})