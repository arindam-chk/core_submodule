project(core_submodule)
cmake_minimum_required(VERSION 3.0)
enable_testing()


include_directories(src)
add_library(core_submodule STATIC src/add.cc)
