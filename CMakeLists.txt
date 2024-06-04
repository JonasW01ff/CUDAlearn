cmake_minimum_required(VERSION 3.26)
project(CUDAlearn CUDA)

set(CMAKE_CUDA_STANDARD 17)

add_executable(CUDAlearn main.cu)

set_target_properties(CUDAlearn PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
