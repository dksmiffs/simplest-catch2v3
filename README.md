# Simplest Known Catch2 v3 Usage

I ran this on WSL using g++-11:

1. Install CMake and a C++ compiler
1. Clone this repo to your local machine
1. `mkdir build` as a sibling to the `source` directory in your working directory
1. `cd build`
1. `cmake -G "Unix Makefiles" ../source`
1. `cmake --build .`
1. `./tests`
