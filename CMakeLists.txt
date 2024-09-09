# Minimum required CMake version
cmake_minimum_required(VERSION 3.5)

# Project name
project(esp32_wifi_provisioning_example)

# Set the IDF path (adjust this to your actual IDF installation path)
set(IDF_PATH "/path/to/esp-idf")

# Include ESP-IDF build system
include($ENV{IDF_PATH}/tools/cmake/project.cmake)

# Add your source files
list(APPEND EXTRA_COMPONENT_DIRS "${CMAKE_CURRENT_SOURCE_DIR}/components")
set(EXTRA_COMPONENT_DIRS ${EXTRA_COMPONENT_DIRS})

# Add ESP-IDF components
idf_component_register(SRCS "main.c"
                       INCLUDE_DIRS "")

# Set target-specific compiler options (if needed)
target_compile_options(${COMPONENT_LIB} PRIVATE
    -Wall
    -Wextra
    # Add other options here
)
