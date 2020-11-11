cmake_minimum_required(VERSION 3.18)
project(bloom_filter)
set(CMAKE_CXX_STANDARD 14)

set(CMAKE_INSTALL_PREFIX /Users/tubetrue01/desktop/bloom-filter)

aux_source_directory(src SOURCE_PATH)

add_executable(main ${SOURCE_PATH})
