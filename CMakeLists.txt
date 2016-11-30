cmake_minimum_required(VERSION 3.6)
project(esp32_rtos_webclient)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    main/http_request_main.c)

add_executable(esp32_rtos_webclient ${SOURCE_FILES})