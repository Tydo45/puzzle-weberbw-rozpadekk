cmake_minimum_required(VERSION 3.26)
project(SPA5)

set(CMAKE_CXX_STANDARD 17)

add_executable(SPA5 GameRunner.cpp
        Map.h
        Map.cpp
        MapCell.h
        MapCell.cpp
        RoomEvent.h
        RoomEvent.cpp)
