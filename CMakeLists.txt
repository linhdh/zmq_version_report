cmake_minimum_required(VERSION 4.0)
project(zmq_version_report)

set(CMAKE_CXX_STANDARD 17)

add_executable(zmq_version_report main.cpp
        zhelpers.h)

target_link_libraries(zmq_version_report zmq)
