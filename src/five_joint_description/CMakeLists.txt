cmake_minimum_required(VERSION 3.8)
project(five_joint_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY
    urdf
    rviz
    cad
  DESTINATION share/${PROJECT_NAME}
)

ament_package()