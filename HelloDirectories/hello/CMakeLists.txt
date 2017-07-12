set(HELLO_SOURCES
    Hello.cpp
    RunHello.cpp)

add_executable(RunHello ${HELLO_SOURCES})

add_library(LibHello ${HELLO_SOURCES})
target_include_directories(LibHello PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
