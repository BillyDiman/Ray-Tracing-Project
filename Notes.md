# Notes

## CMake

CMakeLists.txt - Contains the project name, executable name, and the files that should be compiled
Commands
- cmake -B build/Release -DCMAKE_BUILD_TYPE=Release
- cmake --build build/Release


## Design Choices

- Floats instead of doubles because they take up half the space (4 Bytes vs. 8)