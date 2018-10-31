cmake_minimum_required(VERSION 3.10)

project(idk LANGUAGES C)

add_executable(idk main.c)

install(TARGETS idk RUNTIME DESTINATION bin)
