cmake_minimum_required(VERSION 3.10)

project(tlsf)

add_library(${PROJECT_NAME} STATIC)

target_sources(${PROJECT_NAME} PRIVATE include/tlsf/tlsf.c)

target_include_directories(${PROJECT_NAME} PUBLIC include)
