cmake_minimum_required(VERSION 3.1)
project(tiago_bringup)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY config launch
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})