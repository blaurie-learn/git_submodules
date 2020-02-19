CMAKE_MINIMUM_REQUIRED(VERSION 3.12)
PROJECT(git_submodules)

ADD_SUBDIRECTORY(extern/blib)

ADD_EXECUTABLE(git_submodules main.c)
TARGET_LINK_LIBRARIES(git_submodules blib)