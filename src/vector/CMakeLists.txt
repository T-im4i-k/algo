file(GLOB_RECURSE VECTOR_FILES
    CONFIGURE_DEPENDS
    "${CMAKE_CURRENT_SOURCE_DIR}/*.hpp")

add_library(vector INTERFACE "${VECTOR_FILES}")
target_include_directories(vector 
INTERFACE "${CMAKE_CURRENT_SOURCE_DIR}/include/")     