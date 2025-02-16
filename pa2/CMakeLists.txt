cmake_minimum_required(VERSION 3.10)
project(pa2)

find_package(opencv REQUIRED)

find_package(Eigen3 CONFIG REQUIRED)

set(CMAKE_CXX_STANDARD 17)


add_executable(pa2 main.cpp rasterizer.hpp rasterizer.cpp global.hpp Triangle.hpp Triangle.cpp)

target_link_libraries(pa2 ${OpenCV_LIBRARIES} Eigen3::Eigen)
