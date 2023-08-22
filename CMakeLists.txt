cmake_minimum_required(VERSION 3.16.3)

project(shinjuku_map)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY map
  DESTINATION share/${PROJECT_NAME})

ament_package()
