#
# Metal Framework
# Deepak Shenoy
# January 2026
#

cmake_minimum_required(VERSION 4.0)
project(metal_framework)

set(CMAKE_CXX_STANDARD 20)
add_subdirectory(metal-cmake)

add_executable(metal_framework compute-to-render.cpp)
target_link_libraries(metal_framework METAL_CPP)
