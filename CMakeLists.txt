cmake_minimum_required(VERSION 3.10)
project(FactorOracleString)

set(CMAKE_CXX_STANDARD 11)

add_executable(FactorOracleString FactorOracle.cpp FactorOracle.h main.cpp test_lcs.cpp catch2.hpp catch.hpp test_add_letter.cpp test_find_better.cpp test_integral.cpp test_fos.cpp)