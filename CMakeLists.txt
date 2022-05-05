# cmake_minimum_required(VERSION <specify CMake version here>)
project(C_Library_Project)

set(CMAKE_CXX_STANDARD 14)

include_directories(Library)

add_executable(C_Library_Project
        Library/Book.cpp
        Library/Book.h
        Library/Library.cpp
        Library/Student.cpp
        Library/Student.h)
