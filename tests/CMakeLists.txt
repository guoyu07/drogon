link_libraries(drogon trantor uuid pthread jsoncpp dl z)
if(OpenSSL_FOUND)
link_libraries(ssl crypto)
endif()
add_executable(cache_map_test CacheMapTest.cc)
add_executable(cookies_test CookiesTest.cc)
add_executable(class_name_test ClassNameTest.cc)
add_executable(sha1_test Sha1Test.cc)

