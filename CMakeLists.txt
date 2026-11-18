
cmake_minimum_required(VERSION 4.3)
project(CG_Esqueleto)

set(CMAKE_CXX_STANDARD 20)

find_package(OpenGL REQUIRED)
find_package(GLUT REQUIRED)
include_directories(GL)

add_executable(CG_Esqueleto main.cpp)

target_link_libraries(CG_Esqueleto -lglut -lGLU -lGL)