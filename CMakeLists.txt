
cmake_minimum_required(VERSION 3.5)
project(cmc)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

set(CMC_INCLUDE ${CMAKE_CURRENT_SOURCE_DIR}/src)

add_subdirectory(src)
add_subdirectory(benchmarks)
add_subdirectory(examples)
add_subdirectory(tests)
