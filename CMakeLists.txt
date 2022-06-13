cmake_minimum_required(VERSION 3.21)
project(philosophers2 C)

set(CMAKE_C_STANDARD 99)

add_executable(philosophers2 actions.c other.c philo.c philo.h)
