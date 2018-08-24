cmake_minimum_required(VERSION 3.12)
project(untitled)


link_libraries(glog  gflags opencv_core opencv_highgui opencv_imgcodecs opencv_imgproc)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp)