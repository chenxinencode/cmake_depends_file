cmake_minimum_required(VERSION 2.8.4)
project(test)
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
#set(CMAKE_CXX_COMPILER /path/to/cpp/compiler)
aux_source_directory(. SRC_CUR)#搜索当前目录
add_executable(out ${SRC_CUR})#根据源文件生成可执行文件kalman.exe
