cmake_minimum_required (VERSION 2.8.11)

# Project details.
project (StockAnalyzer)

set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

SET(${PROJECT_NAME}_MAJOR_VERSION 1)
SET(${PROJECT_NAME}_MINOR_VERSION 0)
SET(${PROJECT_NAME}_PATCH_LEVEL 0)

add_executable(output main.cpp table.cpp Graph.cpp)
add_definitions ("-w")

