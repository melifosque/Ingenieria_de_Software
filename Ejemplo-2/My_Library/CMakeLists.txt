add_library(My_Library SHARED
            My_Library.hpp
            My_Library.cpp)

target_include_directories(My_Library PUBLIC
            ${CMAKE_CURRENT_LIST_DIR})   