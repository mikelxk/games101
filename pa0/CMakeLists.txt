cmake_minimum_required (VERSION 3.10)

project (pa0)

add_executable (pa0 main.cpp)

target_link_libraries (pa0 Eigen3::Eigen)