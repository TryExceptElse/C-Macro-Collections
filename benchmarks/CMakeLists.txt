add_executable(benchmark benchmark.c)
target_include_directories(benchmark PUBLIC ${CMC_INCLUDE})
target_link_libraries(benchmark m)
