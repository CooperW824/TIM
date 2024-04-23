cmake_minimum_required(VERSION 3.0)

project(AppName)

set(CMAKE_CXX_STANDARD 23)

set(SOURCE_FILES
    src/main.cpp
)

set(CMAKE_BUILD_TYPE Debug)

add_executable(AppName ${SOURCE_FILES})

set_target_properties(${PROJECT_NAME} PROPERTIES OUTPUT_NAME "app.out")
