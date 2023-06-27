cmake_minimum_required(VERSION 3.5)
project(snapped_ros2_pkg)

# Default to C99
if(NOT CMAKE_C_STANDARD)
  set(CMAKE_C_STANDARD 99)
endif()

# Default to C++14
if(NOT CMAKE_CXX_STANDARD)
  set(CMAKE_CXX_STANDARD 17)
endif()

if(CMAKE_COMPILER_IS_GNUCXX OR CMAKE_CXX_COMPILER_ID MATCHES "Clang")
  add_compile_options(-Wall -Wextra -Wpedantic)
endif()

# find dependencies
find_package(ament_cmake REQUIRED)
find_package(geometry_msgs REQUIRED)
find_package(rclcpp REQUIRED)

add_executable(snapped_ros2_pkg_node src/snapped_ros2_pkg_node.cpp)
add_executable(snapped_ros2_pkg_node1 src/snapped_ros2_pkg_node1.cpp)
add_executable(snapped_ros2_pkg_node2 src/snapped_ros2_pkg_node2.cpp)
add_executable(snapped_ros2_pkg_node3 src/snapped_ros2_pkg_node3.cpp)
add_executable(snapped_ros2_pkg_node4 src/snapped_ros2_pkg_node4.cpp)
add_executable(snapped_ros2_pkg_node5 src/snapped_ros2_pkg_node5.cpp)
add_executable(snapped_ros2_pkg_node6 src/snapped_ros2_pkg_node6.cpp)
add_executable(snapped_ros2_pkg_node7 src/snapped_ros2_pkg_node7.cpp)
add_executable(snapped_ros2_pkg_node8 src/snapped_ros2_pkg_node8.cpp)
add_executable(snapped_ros2_pkg_node9 src/snapped_ros2_pkg_node9.cpp)
add_executable(snapped_ros2_pkg_node10 src/snapped_ros2_pkg_node10.cpp)
add_executable(snapped_ros2_pkg_node11 src/snapped_ros2_pkg_node11.cpp)
add_executable(snapped_ros2_pkg_node12 src/snapped_ros2_pkg_node12.cpp)
add_executable(snapped_ros2_pkg_node13 src/snapped_ros2_pkg_node13.cpp)
add_executable(snapped_ros2_pkg_node14 src/snapped_ros2_pkg_node14.cpp)
add_executable(snapped_ros2_pkg_node15 src/snapped_ros2_pkg_node15.cpp)
add_executable(snapped_ros2_pkg_node16 src/snapped_ros2_pkg_node16.cpp)
add_executable(snapped_ros2_pkg_node17 src/snapped_ros2_pkg_node17.cpp)
add_executable(snapped_ros2_pkg_node18 src/snapped_ros2_pkg_node18.cpp)
add_executable(snapped_ros2_pkg_node19 src/snapped_ros2_pkg_node19.cpp)

target_include_directories(snapped_ros2_pkg_node PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node1 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node2 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node3 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node4 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node5 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node6 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node7 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node8 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node9 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node10 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node11 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node12 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node13 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node14 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node15 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node16 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node17 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node18 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)
target_include_directories(snapped_ros2_pkg_node19 PUBLIC
  $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
  $<INSTALL_INTERFACE:include>)

ament_target_dependencies(snapped_ros2_pkg_node rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node1 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node2 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node3 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node4 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node5 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node6 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node7 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node8 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node9 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node10 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node11 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node12 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node13 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node14 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node15 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node16 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node17 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node18 rclcpp geometry_msgs)
ament_target_dependencies(snapped_ros2_pkg_node19 rclcpp geometry_msgs)

install(TARGETS snapped_ros2_pkg_node
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node1
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node2
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node3
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node4
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node5
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node6
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node7
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node8
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node9
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node10
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node11
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node12
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node13
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node14
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node15
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node16
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node17
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node18
  DESTINATION lib/${PROJECT_NAME})
install(TARGETS snapped_ros2_pkg_node19
  DESTINATION lib/${PROJECT_NAME})

install(DIRECTORY
  launch
  DESTINATION share/${PROJECT_NAME})

install(DIRECTORY
  config
  DESTINATION share/${PROJECT_NAME})

if(BUILD_TESTING)
  find_package(ament_lint_auto REQUIRED)
  # the following line skips the linter which checks for copyrights
  # uncomment the line when a copyright and license is not present in all source files
  #set(ament_cmake_copyright_FOUND TRUE)
  # the following line skips cpplint (only works in a git repo)
  # uncomment the line when this package is not in a git repo
  #set(ament_cmake_cpplint_FOUND TRUE)
  ament_lint_auto_find_test_dependencies()
endif()

ament_package()
