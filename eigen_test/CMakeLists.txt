cmake_minimum_required(VERSION 3.24)
project(eigen_example LANGUAGES CXX)

include(FetchContent)
set(EIGEN_BUILD_TESTING OFF CACHE BOOL "Build Eigen's full test suite")
set(EIGEN_BUILD_DOC OFF CACHE BOOL "Build Eigen documentation")
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
FetchContent_Declare(
  eigen
  GIT_REPOSITORY https://gitlab.com/libeigen/eigen.git
  GIT_TAG 5.0.1
  GIT_SHALLOW TRUE
)
FetchContent_MakeAvailable(eigen)

add_executable(eigen_example main.cpp)
target_compile_features(eigen_example PRIVATE cxx_std_23)
target_link_libraries(eigen_example PRIVATE Eigen3::Eigen)

enable_testing()
add_test(NAME fixed_size_example COMMAND eigen_example)
