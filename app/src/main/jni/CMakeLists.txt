cmake_minimum_required(VERSION 3.6)

add_library(photoEditor SHARED photoEditor.c)

target_link_libraries(photoEditor android)