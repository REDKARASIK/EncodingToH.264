cmake_minimum_required(VERSION 3.5.0)
project(EncodeToH264 C
        VERSION 1.0
        DESCRIPTION "C library for encoding hdi-sdi to h.264"
        LANGUAGES C
)

set(CMAKE_C_STANDARD 17)
add_subdirectory(bin)
add_subdirectory(lib)