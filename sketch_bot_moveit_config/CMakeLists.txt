cmake_minimum_required(VERSION 3.10)
project(sketch_bot_moveit_config)

find_package(ament_cmake REQUIRED)

install(DIRECTORY config launch srdf urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
