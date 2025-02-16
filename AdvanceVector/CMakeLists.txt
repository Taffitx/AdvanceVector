# Set cmake version
cmake_minimum_required(VERSION 3.11)

# Set the project name
project(AdvanceVectorProject)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add the executable 
add_executable(AdvanceVector src/main.cpp)

# Specify the include directories
target_include_directories(AdvanceVector PUBLIC include)