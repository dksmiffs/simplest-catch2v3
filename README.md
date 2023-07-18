# Simplest known Catch2 v3 usage

On some Linux flavor, no sudo required:

1. Assumes CMake and a C++ compiler are available
1. Clone this repo to your local machine
1. `mkdir build` as a sibling to the `src` directory in your working directory
1. `cd build`
1. `cmake -S ../src -B .`
1. `cmake --build .`
1. `./tests`
