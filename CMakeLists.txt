cmake_minimum_required(VERSION 4.3)
project(CS210_GitHub)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CS210_GitHub
        loadbalancer.cpp
        loadbalancer.h
        p2.cpp
        request.h
        webserver.cpp
        loadbalancer.cpp)
