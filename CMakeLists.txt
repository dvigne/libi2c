cmake_minimum_required(VERSION 3.10)
project(libi2c)

include_directories(include)
add_library(libi2c STATIC src/i2c.c)
