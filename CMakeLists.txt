# Set the required version of CMake
cmake_minimum_required(VERSION 2.8)
# Set your project title
project(ME759_Homework)

#The following will but all binary files in a "bin" directory
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

#Add subdirectories for each homework
add_subdirectory(homework_01)
add_subdirectory(homework_02)
