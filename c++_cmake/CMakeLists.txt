cmake_minimum_required(VERSION 3.10)

project(wifiSniffer LANGUAGES CXX)

include_directories(${PROJECT_SOURCE_DIR})
add_library(lib path to .cpp )


add_executable(run main.cpp)
target_link_libraries(run lib)