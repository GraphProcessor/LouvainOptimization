cmake_minimum_required(VERSION 3.6)
project(origin-louvain)

add_executable(commumity_bin main_community.cpp community.cpp graph_binary.cpp graph_binary.h)
add_executable(convert_bin main_convert.cpp graph.cpp)
add_executable(hierarchy_bin main_hierarchy.cpp)

add_executable(playground0 playground/main_random.cpp)