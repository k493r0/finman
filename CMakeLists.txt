cmake_minimum_required(VERSION 3.21)
project(finman)

set(CMAKE_CXX_STANDARD 14)
add_executable(finman main.cpp lib/sqlite3.h lib/sqlite3.c config.h config.cpp config.h)
