cmake_minimum_required(VERSION 3.0)
project(glad C)

add_library(glad)
set_property(TARGET glad PROPERTY C_STANDARD 99)

target_sources(glad PRIVATE "src/gl.c")
target_include_directories(glad PUBLIC "include")
