cmake_minimum_required(VERSION 3.21.4)
project(randutils VERSION 0.0.0.1 LANGUAGES CXX)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(${PROJECT_NAME} INTERFACE ${PROJECT_SOURCE_DIR})
target_compile_features(${PROJECT_NAME} INTERFACE cxx_std_11)