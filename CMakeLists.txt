cmake_minimum_required(VERSION 3.10)
project(shell)

set(CMAKE_CXX_STANDARD 17)

add_executable(shell
    src/main.cpp
    src/parser.cpp
    src/executer.cpp
    src/builtins.cpp
)
