project(legendre-2)

add_executable(${PROJECT_NAME} main.cpp)
include (../../../CMake.common)

set(BIN ${PROJECT_BINARY_DIR}/${PROJECT_NAME})
add_test(legendre-2 ${BIN})
set_tests_properties(legendre-2 PROPERTIES COST -3.7)