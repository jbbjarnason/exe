project(exe)
cmake_minimum_required(VERSION 3.21)

add_executable(exe main.cpp)

install(TARGETS exe
	RUNTIME DESTINATION bin)


