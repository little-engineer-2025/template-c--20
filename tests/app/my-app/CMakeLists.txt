
add_executable(
    my_app_main_test
    main_test.cpp
)
target_link_libraries(
    my_app_main_test
    gtest
    gtest_main
    # GTest::gtest_main
)

include(GoogleTest)
# gtest_discover_tests(main_test)

