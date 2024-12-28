cmake_minimum_required(VERSION 3.5)

project(streamprintf LANGUAGES CXX)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 11)
