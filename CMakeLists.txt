# CMakeList.txt : CMake project for sfui, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("sfui")

set (CU_SFML_PATH "C:\\Users\\Administrator\\Documents\\SFML\\SFML-2.5.1") # Modify for your needs
# Add source to this project's executable.
add_executable (sfui "sfui.cpp" "sfui.h")

# Add SFML 2.5.1
set (CU_SFML_LIB)
string(CONCAT CU_SFML_LIB CU_SFML_PATH "\\bin")