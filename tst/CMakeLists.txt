add_executable(sample1_unittest ${CMAKE_SOURCE_DIR}/src/sample1.cc sample1_unittest.cc)
target_link_libraries(sample1_unittest gtest_main pthread)
add_test(NAME sample1_unittest COMMAND sample1_unittest)

add_executable(sample2_unittest ${CMAKE_SOURCE_DIR}/src/sample2.cc sample2_unittest.cc)
target_link_libraries(sample2_unittest gtest_main pthread)
add_test(NAME sample2_unittest COMMAND sample2_unittest)

add_executable(sample3_unittest sample3_unittest.cc)
target_link_libraries(sample3_unittest gtest gtest_main pthread)
add_test(NAME sample3_unittest COMMAND sample3_unittest)

add_executable(sample4_unittest ${CMAKE_SOURCE_DIR}/src/sample4.cc sample4_unittest.cc)
target_link_libraries(sample4_unittest gtest gtest_main pthread)
add_test(NAME sample4_unittest COMMAND sample4_unittest)

add_executable(sample5_unittest ${CMAKE_SOURCE_DIR}/src/sample1.cc sample5_unittest.cc)
target_link_libraries(sample5_unittest gtest gtest_main pthread)
add_test(NAME sample5_unittest COMMAND sample5_unittest)

add_executable(sample6_unittest sample6_unittest.cc)
target_link_libraries(sample6_unittest gtest gtest_main pthread)
add_test(NAME sample6_unittest COMMAND sample6_unittest)

add_executable(sample7_unittest sample7_unittest.cc)
target_link_libraries(sample7_unittest gtest gtest_main pthread)
add_test(NAME sample7_unittest COMMAND sample7_unittest)

add_executable(sample8_unittest sample8_unittest.cc)
target_link_libraries(sample8_unittest gtest gtest_main pthread)
add_test(NAME sample8_unittest COMMAND sample8_unittest)

add_executable(sample9_unittest sample9_unittest.cc)
target_link_libraries(sample9_unittest gtest gtest_main pthread)
add_test(NAME sample9_unittest COMMAND sample9_unittest)

add_executable(sample10_unittest sample10_unittest.cc)
target_link_libraries(sample10_unittest gtest gtest_main pthread)
add_test(NAME sample10_unittest COMMAND sample10_unittest)
