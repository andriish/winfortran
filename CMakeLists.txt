cmake_minimum_required (VERSION 3.15)
project(WINFORTRAN LANGUAGES Fortran)
add_executable(main  main.f)
install(TARGETS main DESTINATION bin)