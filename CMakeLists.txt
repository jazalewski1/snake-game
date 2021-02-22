cmake_minimum_required(VERSION 3.19)

project(SnakeGame LANGUAGES CXX)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

add_executable(snake-game app/Main.cpp)