set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

project(libexecstream)
cmake_minimum_required(VERSION 2.8)

option(LIBEXECSTREAM_SHARED "Build shared library" OFF)
add_subdirectory(src)
