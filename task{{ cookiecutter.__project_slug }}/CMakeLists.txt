cmake_minimum_required(VERSION 3.26)
project({{ cookiecutter.__task_name }})

set(CMAKE_CXX_STANDARD 14)

add_executable({{ cookiecutter.__task_name }} {{ cookiecutter.__task_name }}.cpp)