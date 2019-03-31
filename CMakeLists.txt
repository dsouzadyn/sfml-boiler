cmake_minimum_required(VERSION 3.14)
project(sfmlapp)
set(SOURCE_DIR src)
add_executable(hellosfml ${SOURCE_DIR}/main.cpp)

target_link_libraries(hellosfml -lsfml-graphics)
target_link_libraries(hellosfml -lsfml-window)
target_link_libraries(hellosfml -lsfml-system)
