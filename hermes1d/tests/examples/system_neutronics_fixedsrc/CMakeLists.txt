project(example-system_neutronics_fixedsrc)

add_executable(${PROJECT_NAME} main.cpp)
include (../../../CMake.common)

set(BIN ${PROJECT_BINARY_DIR}/${PROJECT_NAME})
add_test(example-system_neutronics_fixedsrc ${BIN})
set_tests_properties(example-system_neutronics_fixedsrc PROPERTIES WILL_FAIL TRUE)