cmake_minimum_required (VERSION 3.1.0...3.27.0)

project(PathTracing)

set(CMAKE_CXX_STANDARD 		  11)
set(CMAKE_CXX_STANDARD_REQUIRED   True)

set(SOURCE_PATH_TRACING 
 main.cpp
 vec3.h
 color.h
)

add_executable(PathTracing ${SOURCE_PATH_TRACING})
