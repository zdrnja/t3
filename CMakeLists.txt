cmake_minimum_required(VERSION 3.0)

add_compile_options(
  -std=c++17
  -Wall
  -Wextra
  -Wpedantic
  -pie
  -fpie
  -O3
)

project(simple)

add_executable (
  hello2.executable
  hello2.cpp
)
