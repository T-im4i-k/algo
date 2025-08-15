cmake_minimum_required(VERSION 4.0)

project(algo 
        DESCRIPTION "The project implements a library containing some popular algorithms and data structures."
        LANGUAGES CXX)

set(CXX_VERSION 17)
set(CXX_VERSION_REQUIRED TRUE)

add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/src/")
