cmake_minimum_required(VERSION 3.24)
project(libvlengine)

# Project is already pre-pended with lib
set(CMAKE_SHARED_LIBRARY_PREFIX "")
set(CMAKE_STATIC_LIBRARY_PREFIX "")

add_subdirectory(${PROJECT_NAME})