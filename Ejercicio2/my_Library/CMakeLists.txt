add_library(my_Library SHARED
            my_Library.hpp
            my_Library.cpp)

target_include_directories(my_Library PUBLIC
            ${CMAKE_CURRENT_LIST_DIR})   