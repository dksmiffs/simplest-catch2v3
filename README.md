# Simplest known Catch2 v3 usage

On some Linux flavor, no sudo required:

1. Assumes CMake and a C++ compiler are available
1. `git clone` this repo to your local machine
1. `cd simplest-catch2v3`
1. `cmake -S ./src -B ./build`
1. `cmake --build ./build`
1. `./build/tests`

The single test should pass.
