
add_executable(my_tool_main_test main_test.cpp)
target_link_libraries(my_tool_main_test gtest gtest_main)

include(GoogleTest)
gtest_discover_tests(my_tool_main_test)

