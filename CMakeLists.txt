cmake_minimum_required(VERSION 4.3)
project(hangman_cpp)

set(CMAKE_CXX_STANDARD 20)

add_executable(hangman_cpp main.cpp
        models/hangman.cpp
        models/hangman.h
        models/dictionary.cpp
        models/dictionary.h)
