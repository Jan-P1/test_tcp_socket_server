cmake_minimum_required(VERSION 3.21)
project(Test_and_own_code C)

set(CMAKE_C_STANDARD 99)

add_executable(Test_and_own_code main.c server.c server.h client.c client.h)
