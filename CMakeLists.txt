# Inspired from GPT-4o mini

cmake_minimum_required(VERSION 3.10)
project(myApp
    VERSION 0.1.0
    DESCRIPTION "TODO Template for C++ library/application build with cmake"
    LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add subdirectories (libs and app)
add_subdirectory(libs)
add_subdirectory(app)

string(COMPARE EQUAL
    "${CMAKE_SOURCE_DIR}"
    "${CMAKE_CURRENT_SOURCE_DIR}"
    is_top_level)

include(GNUInstallDirs)

# ---------------------------------- TESTS -------------------------------------

# TODO Integrate googletest

# Google tests configuration
enable_testing()

# Define the path to Google Test
set(GTEST_DIR "${CMAKE_CURRENT_SOURCE_DIR}/third_party/googletest/googletest")

# Add Google Test to the build
# add_subdirectory(${GTEST_DIR} ${CMAKE_CURRENT_BINARY_DIR}/googletest)

# add_subdirectory(tests)

