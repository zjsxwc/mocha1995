cmake_minimum_required(VERSION 3.17)
project(mocha1995_main C)

set(CMAKE_C_STANDARD 99)

include_directories(include)
AUX_SOURCE_DIRECTORY(src DIR_SRCS)

add_executable(mocha1995_main main.c ${DIR_SRCS})
