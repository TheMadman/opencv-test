cmake_minimum_required(VERSION 3.10)

project(OpenCVTest)

find_package(OpenCV REQUIRED)

add_executable(foo main.cpp)
target_link_libraries(foo ${OpenCV_LIBS})
