find_package(spdlog REQUIRED)

add_executable(test main.cpp)
target_link_libraries(test PRIVATE spdlog::spdlog_header_only)
