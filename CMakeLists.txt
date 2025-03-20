cmake_minimum_required(VERSION 3.10)
project(AdditionTest)

set(CMAKE_CXX_STANDARD 17)

add_executable(test_runner test.cpp add.cpp)
target_link_libraries(test_runner gtest gtest_main pthread)
