cmake_minimum_required(VERSION 3.10)

project(RapidXML)

set(CMAKE_CXX_STANDARD 17)

add_library(rapidxml INTERFACE)

target_include_directories(rapidxml
	INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}
)
