cmake_minimum_required (VERSION 3.26)

project (HelloWorld)

set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wail -Werror -std=c++14")
set (source_dir "${PROJECT_SOURCE_DIR}/src/")


file (GLOB source_files "${source_dir}/*.cpp")

add_executable (HelloWorld ${source_files})