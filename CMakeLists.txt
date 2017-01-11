cmake_minimum_required (VERSION 3.0.2)
project (wavelet)
add_library(wavelet SHARED wavelet.c)

add_executable(waveletTest waveletTest.c)
target_link_libraries(waveletTest wavelet)