cmake_minimum_required(VERSION 3.1)
project( mat )
find_package( OpenCV REQUIRED )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable( mat mat.cpp )
target_link_libraries( mat ${OpenCV_LIBS} )
