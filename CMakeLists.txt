cmake_minimum_required(VERSION 3.21 FATAL_ERROR)

project(tinyfiledialogs VERSION 1.0.0 LANGUAGES C)

add_library(tinyfiledialogs STATIC tinyfiledialogs.c)
target_include_directories(tinyfiledialogs PUBLIC ${CMAKE_CURRENT_LIST_DIR}/..)