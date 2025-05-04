//
//  CMakeLists.txt
//  Xcodetest
//
//  Created by Lasitha Atapattu on 2025-05-04.
//
enable_testing()
add_executable(test_mylib test_main.cpp test_mylib.cpp)

add_test(NAME MyLibTest COMMAND test_mylib)

