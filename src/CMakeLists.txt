# cmake_minimum_required(VERSION <specify CMake version here>)
project(src)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Tests/test.c
        Tests/test.h
        main.c
        shell.c
        shell.h)

add_executable(src ${SOURCE_FILES})