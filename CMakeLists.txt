cmake_minimum_required(VERSION 2.9)

include_directories(include)

ADD_LIBRARY(stb_image STATIC
  src/stb_image.cpp
)