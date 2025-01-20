cmake_minimum_required(VERSION 3.1)
project(exoCours)

add_executable(exoCours
    3-destructor.cpp
)

target_compile_features(exoCours PUBLIC cxx_std_17)
