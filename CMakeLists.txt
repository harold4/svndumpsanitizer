cmake_minimum_required(VERSION 3.7)
project(svndumpsanitizer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        svndumpsanitizer.c)

add_executable(svndumpsanitizer ${SOURCE_FILES})