cmake_minimum_required(VERSION 3.24)
project(Server_Client_Using_Socket C)

set(CMAKE_C_STANDARD 11)

add_executable(Server_Client_Using_Socket
        client.c
        mirror.c
        server.c)
