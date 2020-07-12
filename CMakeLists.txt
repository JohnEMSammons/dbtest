cmake_minimum_required (VERSION 2.6)

project (dbtest)

add_executable(dbtest dbtest.cpp)

find_package (SQLite3)
include_directories(${SQLite3_INCLUDE_DIRS})
target_link_libraries (dbtest ${SQLite3_LIBRARIES})

