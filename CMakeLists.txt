cmake_minimum_required(VERSION 3.18)

project(learning_ray_tracing)

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_executable(${PROJECT_NAME}
    ${CMAKE_CURRENT_SOURCE_DIR}/main.cc
)