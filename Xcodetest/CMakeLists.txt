//
//  CMakeLists.txt
//  Xcodetest
//
//  Created by Lasitha Atapattu on 2025-05-04.
//
cmake_minimum_required(VERSION 3.14)
project(MyCppProject VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include src and header files
add_subdirectory(src)
add_subdirectory(tests)

