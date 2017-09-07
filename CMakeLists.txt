include_directories(
        inc
        ../common/inc
)
aux_source_directory(src src)
message(DEBUG "c flag= ${CMAKE_C_FLAGS}")
add_library(tomcrypt STATIC ${SRC})