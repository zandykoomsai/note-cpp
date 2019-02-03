cmake_minimum_required (VERSION 2.8)
project (wc CXX C)

add_executable(bound bound.cpp)
add_executable(reverse reverse.cpp)

# setenv.bat
# cmake .. -G"Watcom WMake"
# cmake --build .