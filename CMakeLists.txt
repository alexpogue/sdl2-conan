project(sdl2-conan)
cmake_minimum_required(VERSION 2.8.12)

include(conanbuildinfo.cmake)
conan_basic_setup()

add_executable(sdl2-conan main.cpp)
target_link_libraries(sdl2-conan ${CONAN_LIBS})
