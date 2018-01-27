cmake_minimum_required(VERSION 2.8)

project(MyBicycles)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE 
    main.cpp)

add_executable(${PROJECT_NAME} ${SOURCE})
