cmake_minimum_required(VERSION 3.0.0)

project(tcp_client)

add_executable(${PROJECT_NAME}
    ./tcp_client.c
)

target_compile_options(${PROJECT_NAME} PUBLIC
    -Wall
)