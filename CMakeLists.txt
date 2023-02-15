# Minimum Version
cmake_minimum_required(VERSION 3.20)

# C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Library
add_library("IconFonts" INTERFACE)

# Target properties
target_include_directories("IconFonts" INTERFACE "./")