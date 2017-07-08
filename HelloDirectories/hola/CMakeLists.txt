include_directories(${PROJECT_SOURCE_DIR})
set(HOLA_SOURCES
    Hola.cpp
    RunHola.cpp
    ${PROJECT_SOURCE_DIR}/hello/Hello.cpp)
add_executable(RunHola ${HOLA_SOURCES})
add_dependencies(RunHola RunHello)
