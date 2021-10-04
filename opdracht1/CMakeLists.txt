cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Opdracht1_GPIO_inlezen)

add_executable(Opdracht1 opdracht1.c)
include_directories(/usr/include/mariadb /usr/include/mariadb/mysql)

target_link_libraries(Opdracht1 mariadb PJ_RPI)
