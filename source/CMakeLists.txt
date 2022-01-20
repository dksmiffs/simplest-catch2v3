cmake_minimum_required(VERSION 3.14)

project(helloCatch2v3)

include(FetchContent)
FetchContent_Declare(
  Catch2
  GIT_REPOSITORY https://github.com/catchorg/Catch2.git
  GIT_TAG f4af9f69265d009a457aa99d1075cfba78652a66) # v3.0.0-preview4

FetchContent_MakeAvailable(Catch2)

add_executable(tests test.cpp)
target_link_libraries(tests PRIVATE Catch2::Catch2WithMain)
