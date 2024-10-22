cmake_minimum_required(VERSION 3.16)

project(malloc_1-d_array LANGUAGES C)

add_executable(malloc_1-d_array main.c)

include(GNUInstallDirs)
install(TARGETS malloc_1-d_array
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
