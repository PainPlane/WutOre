cmake_minimum_required( VERSION 3.0.2 )

project( WutOre )

set( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall -Wextra" )

set( PROJECT_SOURCES src/main.cpp )

include_directories( include )

add_executable( ${PROJECT_NAME} ${PROJECT_SOURCES} )

target_link_libraries( ${PROJECT_NAME} )
