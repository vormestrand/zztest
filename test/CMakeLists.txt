cmake_minimum_required(VERSION 2.8.12)
add_executable(uri_test uri_test.cpp)
target_include_directories(uri_test PUBLIC "${CMAKE_SOURCE_DIR}/test/lest/include/lest")
target_link_libraries(uri_test LINK_PUBLIC Uri)
add_test (NAME UriTest COMMAND uri_test)