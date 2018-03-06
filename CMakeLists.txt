cmake_minimum_required( VERSION 2.8 )

project( geometry )

# 设置编译模式
set( CMAKE_BUILD_TYPE "Debug" )

# 添加头文件
include_directories( "/usr/include/eigen3")
 
add_executable( useGeometry useGeometry.cpp )
