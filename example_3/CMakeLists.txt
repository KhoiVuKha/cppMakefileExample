cmake_minimum_required(VERSION 3.5.1)

set(CMAKE_CXX_STANDARD 17)

project(testApp)

add_executable(testApp main.cpp message.cpp)


# TODO: Run -Werror in CI.
target_compile_options(testApp PRIVATE -Wall -Wextra)
