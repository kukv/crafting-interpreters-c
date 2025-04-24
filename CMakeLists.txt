cmake_minimum_required(VERSION 3.31)
project(crafting_interpreters_c C)

set(CMAKE_C_STANDARD 17)

include_directories(.)

add_executable(crafting_interpreters_c
        chunk.c
        chunk.h
        common.h
        debug.c
        debug.h
        main.c
        memory.c
        memory.h
        value.c
        value.h
)
