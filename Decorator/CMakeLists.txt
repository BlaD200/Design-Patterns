cmake_minimum_required(VERSION 3.16)
project(Decorator)

set(CMAKE_CXX_STANDARD 14)

add_executable(Decorator main.cpp ACar.h Car.h CarDecorator.h TyreDecorator.h NitroDecorator.h PaintingDecorator.h)