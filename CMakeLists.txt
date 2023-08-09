add_library(encoder INTERFACE)

target_sources(encoder INTERFACE
 ${CMAKE_CURRENT_LIST_DIR}/encoder.c
)

target_include_directories(encoder INTERFACE ${CMAKE_CURRENT_LIST_DIR})
