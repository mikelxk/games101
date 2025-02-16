cmake_minimum_required(VERSION 3.10)

project(GAMES101)

set(CMAKE_CXX_STANDARD 20)

find_package(Eigen3 CONFIG REQUIRED)
find_package(OpenCV CONFIG REQUIRED)

add_subdirectory(pa0)
add_subdirectory(pa1)
add_subdirectory(pa2)
add_subdirectory(pa3)
add_subdirectory(pa4)
add_subdirectory(pa5)
add_subdirectory(pa6)
add_subdirectory(pa7)
add_subdirectory(pa8)