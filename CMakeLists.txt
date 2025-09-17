cmake_minimum_required(VERSION 4.0)
project(gpgpu-course LANGUAGES C CXX CUDA)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(SOURCES
    src/Main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})