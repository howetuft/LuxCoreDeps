cmake_minimum_required(VERSION 3.10)
project(try-compile)
try_compile(TRY_RESULT SOURCES /Users/runner/work/LuxCoreDeps/LuxCoreDeps/utils/cmake_try_compile/hello.cpp)
message(STATUS ${TRY_RESULT})
