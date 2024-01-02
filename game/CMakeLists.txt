
add_executable(game
        WCSY.c
)
target_compile_features(game PRIVATE c_std_17)

target_link_libraries(game PUBLIC engine)
