cmake_minimum_required(VERSION 3.23)
project(Your_project_name)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS -DLOCAL) // => Use to set #ifdef LOCAL
add_executable(Main main.cpp)
