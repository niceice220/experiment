
cmake_minimum_required(VERSION 3.0.0)
project(experiment_cpp VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 14)
add_executable(smart-point c++11/smart-point.cpp)
add_executable(thread_c11 c++11/thread.cpp)
add_executable(main main.cpp)
add_executable(time time/time.cpp)