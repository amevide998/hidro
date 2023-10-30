cmake_minimum_required(VERSION 3.20)  # CMake version check
project(hidrogen)               # Create project "simple_example"
set(CMAKE_CXX_STANDARD 20)            # Enable c++20 standard

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(hidro src/main.cpp)