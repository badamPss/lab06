cmake_minimum_required(VERSION 3.10)
project(hello_world)
add_executable(hello_world hello_world.cpp)
target_link_libraries(hello_world PRIVATE formatter_ex)
target_include_directories(hello_world PRIVATE ${CMAKE_SOURCE_DIR}/formatter_ex_lib ${CMAKE_SOURCE_DIR}/formatter_lib)