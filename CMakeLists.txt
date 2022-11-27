
cmake_minimum_required(VERSION 3.20)

project(CppSamples)

add_executable(HelloWorld "main.cpp")
set_property(TARGET HelloWorld PROPERTY CXX_STANDARD 20)
