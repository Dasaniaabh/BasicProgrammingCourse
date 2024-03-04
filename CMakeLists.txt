cmake_minimum_required(VERSION 3.26)
project(Lab_14_0 C)

set(CMAKE_C_STANDARD 11)

add_executable(Lab_14_0 test.c
        libs/data_structure/vector/vector.c
        libs/data_structure/vector/vector.h)

add_subdirectory(libs)
target_link_libraries(data_structure)
