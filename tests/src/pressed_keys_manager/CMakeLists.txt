cmake_minimum_required (VERSION 3.9)

include (../../tests.cmake)

project (karabiner_test)

add_executable(
  karabiner_test
  src/test.cpp
  src/pressed_keys_manager_test.cpp
)

target_link_libraries(
  karabiner_test
  test_runner
)
