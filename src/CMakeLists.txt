add_executable(Learn01 main.cpp Math/Math.cpp)

target_include_directories(Learn01 PUBLIC "${PROJECT_SOURCE_DIR}/src/Math")

install(TARGETS Learn01 DESTINATION bin)