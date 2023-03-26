cmake_minimum_required(VERSION 3.2)

project (DesignPattern C CXX)

SET(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/CMakeModules)

# use c++11
if(CMAKE_VERSION VERSION_LESS "3")
    add_definitions(-std=c++11)
else()
    set(CMAKE_CXX_STANDARD 11)
    set(CMAKE_CXX_STANDARD_REQUIRED ON)
endif()



add_subdirectory(codes)