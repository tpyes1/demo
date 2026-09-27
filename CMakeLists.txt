#配置
cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 17)
project(demo VERSION 1.0.0 LANGUAGES CXX)
#第一个随便，是指的是项目名

#编译
add_executable(demo "dev_cpp/demo.cpp")
target_include_directories(demo PRIVATE /include)


#这两个第一个指的是生成的可执行文件的名字