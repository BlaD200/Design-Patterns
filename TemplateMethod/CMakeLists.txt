cmake_minimum_required(VERSION 3.16)
project(TemplateMethod)

set(CMAKE_CXX_STANDARD 14)

add_executable(TemplateMethod main.cpp APizza.h PepperoniPizza.h HawaiianPizza.h TexasPizza.h)