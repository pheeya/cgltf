cmake_minimum_required(VERSION 3.26.0)
project(logc)

add_library(logc src/log.c src/log.h)


target_include_directories(logc PUBLIC src/)
