# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)


include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(wifi_station)


target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/index.html" TEXT)
target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/black.svg" IMAGE)
target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/cloud2.svg" IMAGE)
target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/cloud1.svg" IMAGE)
target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/white.svg" IMAGE)
target_add_binary_data(${CMAKE_PROJECT_NAME}.elf "html/logorm.png" IMAGE)
