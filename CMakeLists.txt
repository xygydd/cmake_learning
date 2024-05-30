cmake_minimum_required(VERSION 3.0.0)

project(
    cmake_
    VERSION 0.0.1
    PROJECT_DESCRIPTION "DEMO"
    PROJECT_HOMEPAGE_URL "https://github.com/xygydd/cmake_learning"
    LANGUAGE C CXX
)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")

include(BuildInfo)

add_subdirectory(src)

add_subdirectory(external)

add_subdirectory(doc)

add_subdirectory(include)

add_subdirectory(test)



