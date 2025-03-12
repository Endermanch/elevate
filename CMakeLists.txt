cmake_minimum_required(VERSION 3.30)
project(quiet C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} -Wl,-subsystem,windows -municode")

add_executable(
    quiet
    main.c
)
