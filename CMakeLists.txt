cmake_minimum_required(VERSION 3.22)
project(Breakout)

set(CMAKE_CXX_STANDARD 17)
add_subdirectory(../JediEngine/Core Core)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} Core)
