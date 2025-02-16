cmake_minimum_required(VERSION 3.10)

project(pa1)

add_executable(pa1 main.cpp rasterizer.hpp rasterizer.cpp Triangle.hpp Triangle.cpp)

target_link_libraries(pa1 ${OpenCV_LIBRARIES} Eigen3::Eigen)
