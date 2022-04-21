cmake_minimum_required(VERSION 3.21)
project(stb_image C)

add_library(stb_image)
target_sources(stb_image PRIVATE src/stb_image.c)
target_include_directories(stb_image PUBLIC include)

set_property(TARGET stb_image PROPERTY C_STANDARD 99)