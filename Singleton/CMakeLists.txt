cmake_minimum_required(VERSION 3.16)
project(Singleton)

set(CMAKE_CXX_STANDARD 14)

add_executable(Singleton main.cpp StaticMemorySingleton.h DynamicMemorySingleton.h DynamicMemorySingleton.cpp)