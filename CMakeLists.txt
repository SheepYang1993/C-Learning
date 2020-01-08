# cmake_minimum_required(VERSION <specify CMake version here>)
project(c_day1 C)

set(CMAKE_C_STANDARD 99)

add_executable(c_day1 main.c)

# 取消警告
set(ignoreMe "${FOO}${BAZ}${BAR}")