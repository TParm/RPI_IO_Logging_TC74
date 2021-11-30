cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(IO_Logging)

add_executable(IO_Logging IO_Logging.c)
include_directories(/usr/include/mariadb /usr/include/mariadb/mysql)

target_link_libraries(IO_Logging mariadb PJ_RPI)
