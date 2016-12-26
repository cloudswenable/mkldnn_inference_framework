cmake_minimum_required(VERSION 3.6)
project(mkldnn_inference_framework)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp src/CaffeTranslater.cpp include/CaffeTranslater.h)
add_executable(mkldnn_inference_framework ${SOURCE_FILES})