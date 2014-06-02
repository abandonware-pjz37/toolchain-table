cmake_minimum_required(VERSION 3.0)
project(Foo)

add_executable(foo foo.cpp)

enable_testing()
add_test(Foo foo)
