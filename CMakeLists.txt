cmake_minimum_required(VERSION 2.8.3)
project(viwo)

set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_FLAGS "-std=c++14")
#-DEIGEN_USE_MKL_ALL")
set(CMAKE_CXX_FLAGS_RELEASE "-O3 -Wall -g")

add_subdirectory(camera_models)
add_subdirectory(global_fusion)
add_subdirectory(loop_fusion)
add_subdirectory(vins_estimator)
