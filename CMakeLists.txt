cmake_minimum_required(VERSION 3.19)
project(FirstApp)

set(CMAKE_CXX_STANDARD 20)


add_executable(FirstApp main.cpp)

find_package(glfw3 3.3 REQUIRED)
target_link_libraries(FirstApp glfw)

#find_package(glad REQUIRED)
#target_link_libraries(FirstAPP glad)
target_link_libraries(FirstApp /home/riki/Documents/Learn/LearnOpenGL/Libs/glad/libglad.a)