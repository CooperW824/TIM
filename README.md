# CMake-cpp-template
A simple C++ template using CMake for building

## Setting Up

1. To get your project started adjust the `project(AppName)` to reflect the projects name.
2. Run the clean build task to create the build folder and initialize the CMake Project. (Ctrl + Shift + P) then Tasks: Run Task -> clean build.
3. Use the debug terminal to debug your project.

## Adding Source Files

To add source files, update the `set(SOURCE_FILES src/main.cpp)` line to use all of the source files desired.

## Building from Terminal

Use the following command after running the clean build task. This will build the project utilizing 4 threads to compile. 

        cmake --build build -- -j 4
