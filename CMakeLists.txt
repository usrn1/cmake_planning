cmake_minimum_required(VERSION 3.10)
project(planning)
set(CMAKE_CXX_STANDARD 17)

set(EXECUTABLE_OUTPUB_PATH ${PROJECT_SOURCE_DIR}/bin)
aux_source_directory(. SRC_LISTS)
add_executable(planning_main ${SRC_LISTS})