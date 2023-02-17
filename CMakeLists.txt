cmake_minimum_required(VERSION 3.23)
project(CEN4078Project1 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(CEN4078Project1
        client.c
        server.c
        tcpSC.h)
