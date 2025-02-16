cmake_minimum_required(VERSION 3.10)
project(pa4)

add_executable(pa4 main.cpp)
    
target_link_libraries(pa4 ${OpenCV_LIBRARIES} Eigen3::Eigen)
