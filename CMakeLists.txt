# This file was added just for syntax highlighting in CLion
cmake_minimum_required(VERSION 3.10)
project(lab3)

set(CMAKE_CXX_STANDARD 14)
file(GLOB YLAVM_SRC
        "*.h"
        "*.c"
        )
add_executable(main ${YLAVM_SRC})