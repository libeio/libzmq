cmake_minimum_required(VERSION 2.8.0)

include_directories(.)

add_executable(test test.cpp)
target_link_libraries(test ${zmq_LIBRARY_NAME})