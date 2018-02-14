cmake_minimum_required(VERSION 3.9)
project(Socket_Programming C)

set(CMAKE_C_STANDARD 11)

add_executable(Socket_Programming showip.c)
add_executable(server server.c)
add_executable(client client.c)