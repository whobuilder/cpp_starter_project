find_package(docopt)
find_package(fmt)
add_executable(intro main.cpp)
target_link_libraries(
  intro
  PRIVATE project_options
          project_warnings fmt::fmt docopt)
