CMAKE_MINIMUM_REQUIRED(VERSION 2.8.0)

project(project1)
find_package(OpenCV REQUIRED)
add_executable(project1 project1.cpp)
target_link_libraries(project1 ${OpenCV_LIBS})
