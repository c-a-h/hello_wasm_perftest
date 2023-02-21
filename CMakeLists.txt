# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("hello_wasm_perftest")

# Include sub-projects.
add_subdirectory ("hello_wasm_perftest")
