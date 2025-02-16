cmake_minimum_required(VERSION 3.10)

project(pa3)

add_executable(pa3 main.cpp rasterizer.hpp rasterizer.cpp global.hpp Triangle.hpp Triangle.cpp Texture.hpp Texture.cpp Shader.hpp OBJ_Loader.h)

target_link_libraries(pa3 ${OpenCV_LIBRARIES} Eigen3::Eigen)
