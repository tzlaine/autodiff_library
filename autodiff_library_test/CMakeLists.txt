include_directories(${CMAKE_SOURCE_DIR}/autodiff_library/src)

add_executable(
    autodiff_library_test
    src/autodiff_library_test.cpp
)

target_link_libraries(
    autodiff_library_test
    autodiff_library
)
