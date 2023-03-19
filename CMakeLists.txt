project(demo_depend_lib)

add_library(${PROJECT_NAME}
    src/line.cpp
)
target_include_directories(${PROJECT_NAME} PUBLIC
    ${PROJECT_SOURCE_DIR}/include
)
