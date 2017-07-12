set(HOLA_SOURCES
    Hola.cpp
    RunHola.cpp
    )

add_executable(RunHola ${HOLA_SOURCES})
target_link_libraries(RunHola LibHello)
