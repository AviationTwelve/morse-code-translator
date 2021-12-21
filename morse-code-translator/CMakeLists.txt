# CMakeList.txt : CMake project for morse-code-translator, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_executable (morse-code-translator "main.cpp"  "translator.cpp" "translator.h" "dictionary/morse.cpp" "dictionary/morse.h")

# TODO: Add tests and install targets if needed.
