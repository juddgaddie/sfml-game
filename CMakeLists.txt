cmake_minimum_required(VERSION 3.23)
project(sfml_game)

set(CMAKE_CXX_STANDARD 14)

include_directories("include")
link_directories("lib")
add_executable(sfml_game main.cpp)
target_link_libraries(sfml_game sfml-graphics sfml-window sfml-system sfml-audio)
