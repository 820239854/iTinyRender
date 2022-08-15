cmake_minimum_required(VERSION 3.23)
project(iTinyRender)

set(CMAKE_CXX_STANDARD 14)

set(SOURCES
        src/tgaimage.cpp
        src/main.cpp
        )

add_executable(iTinyRender ${SOURCES})

target_include_directories(iTinyRender
        PRIVATE
        ${PROJECT_SOURCE_DIR}/include
)
