cmake_minimum_required(VERSION 3.15)
project(untitled2)

set(CMAKE_CXX_STANDARD 11)
include_directories("/usr/local/include" "/usr/local/opt/llvm/include")
link_directories("/usr/local/lib" "/usr/local/opt/llvm/lib")
set(CMAKE_CXX_COMPILER "/usr/bin/mpic++")
add_executable(untitled2 main.cpp)