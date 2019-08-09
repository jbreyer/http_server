cmake_minimum_required(VERSION 3.14)
project(http_server C)

set(CMAKE_C_STANDARD 99)

add_executable(http_server http.c)