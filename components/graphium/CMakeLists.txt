# Минимальная версия CMake, пригодная для сборки
cmake_minimum_required(VERSION 3.5)

# Регистрация компонента в ESP-IDF
idf_component_register(
    SRCS "graphium.c"
    INCLUDE_DIRS "include"
)