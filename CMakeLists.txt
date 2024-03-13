cmake_minimum_required(VERSION 3.28)

project(simple-win-app-with-res VERSION 0.1 LANGUAGES CXX)

add_definitions(-DUNICODE -D_UNICODE)

add_executable(simple-win-app-with-res WIN32
	simple-win-app-with-res.cpp
	simple-win-app-with-res.h
	simple-win-app-with-res.rc)

