cmake_minimum_required(VERSION 2.8.4)
project(iptables_mini)


include_directories(${PROJECT_SOURCE_DIR})

file(GLOB_RECURSE iptables_mini_files *.h *.c)

add_library(iptables_mini_l STATIC ${iptables_mini_files})
