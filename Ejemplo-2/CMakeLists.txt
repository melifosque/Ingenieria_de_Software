cmake_minimum_required(VERSION 3.8)

# Nombre del proyecto
project(helloWordProyect)

add_subdirectory(My_Library)

add_executable(main main.cpp)

target_link_libraries(main My_Library)