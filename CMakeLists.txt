cmake_minimum_required(VERSION 3.12)

project(homework2)

add_executable(homework2
    hello_world.cpp
    example.cpp 
    move_me_out.cpp 
    example.h 
    move_me_out.h 
)

set_target_properties(homework2 PROPERTIES 
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON 
)