cmake_minimum_required (VERSION 3.2)
project(acl_compressor_root)

if(PLATFORM_ANDROID)
	add_subdirectory("${PROJECT_SOURCE_DIR}/main_android")
else()
	add_subdirectory("${PROJECT_SOURCE_DIR}/main_generic")
endif()
