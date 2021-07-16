cmake_minimum_required(VERSION 3.12)

include(cmake/HunterGate.cmake)
HunterGate(
    URL "https://github.com/cpp-pm/hunter/archive/v0.23.312.tar.gz"
    SHA1 "42311324f6b859983d833cffc2151d0b86b8bea4"
)

project(freeglut)

add_subdirectory(freeglut/freeglut)
