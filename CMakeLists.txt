cmake_minimum_required(VERSION 3.1)
project(stretch_description VERSION 1.0)

find_package(catkin)

catkin_package()

install(DIRECTORY meshes urdf
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
