cmake_minimum_required(VERSION 2.8.7)
add_library(Uri uri.cpp)
target_include_directories(Uri PUBLIC ${CMAKE_SOURCE_DIR}/include)