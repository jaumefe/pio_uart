cmake_minimum_required(VERSION 3.13)
project(uart_pio_lib C CXX ASM)

add_library(uart_pio
    src/uart_pio.c
)

target_include_directories(uart_pio PUBLIC include)