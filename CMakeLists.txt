cmake_minimum_required(VERSION 3.22)
project(numerical_task_7)

set(CMAKE_CXX_COMPILER g++-12)
add_compile_options(-Wall -Wextra -Wfloat-equal -Wundef -Wcast-align -Wwrite-strings -Wlogical-op -Wmissing-declarations -Wredundant-decls -Wshadow -Woverloaded-virtual -pedantic)
set(CMAKE_CXX_STANDARD 20)

add_executable(numerical_task_7 main.cpp fft.cpp fft.h)
