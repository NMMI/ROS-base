cmake_minimum_required(VERSION 3.0.2 FATAL_ERROR)
project(qb_device_msgs VERSION 2.1.0 LANGUAGES CXX)

# Dependency Settings
find_package(catkin REQUIRED
  COMPONENTS
    std_msgs
    message_generation
)

add_message_files(
  DIRECTORY msg
  FILES
    Info.msg
    ResourceData.msg
    State.msg
    StateStamped.msg
)

generate_messages(
  DEPENDENCIES
    std_msgs
)

include_directories(include
  ${catkin_INCLUDE_DIRS}
)

catkin_package(
  INCLUDE_DIRS
    include
  CATKIN_DEPENDS
    std_msgs
    message_runtime
)

# Installation
install(
  DIRECTORY
    include/${PROJECT_NAME}/
  DESTINATION
    ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
)