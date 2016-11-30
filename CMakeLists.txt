cmake_minimum_required(VERSION 3.6)
project(4TC_TP2_PRF)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_C_FLAGS "-lm")

set(SOURCE_FILES buffer.c fes.c fes.h fifo.c fifo.h packet.c packet.h rng.c rng.h)
add_executable(4TC_TP2_PRF ${SOURCE_FILES})