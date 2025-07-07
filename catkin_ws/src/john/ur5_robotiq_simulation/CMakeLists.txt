cmake_minimum_required(VERSION 3.0.2)

project(ur5_robotiq_simulation)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY config launch urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})