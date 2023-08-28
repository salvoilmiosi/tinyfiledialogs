cmake_minimum_required(VERSION 3.13.0)
project(tinyfiledialogs VERSION 0.1.0)

add_library(tinyfiledialogs STATIC tinyfiledialogs.c)
target_include_directories(tinyfiledialogs PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})