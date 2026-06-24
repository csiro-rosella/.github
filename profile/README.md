https://research.csiro.au/fdmf/rosella/

## Data Pipeline

| Repository | Description |
|--------------|-------------|
| [gst_ros2_clock](https://github.com/csiro/cvmiam-gst_ros2_clock) | This GStreamer plugin provides a GstClock implementation that returns timestamps received from the ROS2 /clock topic or directly from an rclclock_t object. |

## Hardware Control

| Repository | Description |
|--------------|-------------|
| [scanner_python_control](https://github.com/csiro/cvmiam-scanner_python_control) | Provides a sample Python code base interaction to do imaging with the robot arm and turntable with using the Zivid camera. |
| [cvmiam_rosbag](https://github.com/csiro/cvmiam-cvmiam_rosbag) | Provides a meta package that contains the configuration for rosbag to capture topics that can be used to process 3D reconstructions. |
| [moveit_csiro_pkg](https://github.com/csiro/cvmiam-moveit_csiro_pkg) | Provides a simple Moveit Action Server to deal with Interactions with MoveIt through ROS2. |
| [pololu_tic_ros2](https://github.com/csiro/cvmiam-pololu_tic_ros2) | wrapper of the pololu tic driver to ROS2. |
| [polulu_tic_ros_pkg](https://github.com/csiro/cvmiam-polulu_tic_ros_pkg) | provides ROS2 server to interface with the Tic driver. |
| [zivid_csiro_pkg](https://github.com/csiro/cvmiam-zivid_csiro_pkg) | provides ROS2 services to interface with the Zivid ROS2 driver. |
| [zivid_turn_ros_pkg](https://github.com/csiro/cvmiam-zivid_turn_ros_pkg) | provides a module to structure an interface between Turntable and Zivid services and servers and provide a simple interface to control Zivid and Tic Turntable. |
| [ur_scanner_cvmiam_pkg](https://github.com/csiro/cvmiam-ur_scanner_cvmiam_pkg) | Contains the MoveIt configurations and robot models for UR5e, Zivid and workspace environment. |

## 3D Vision

| Repository | Description |
|--------------|-------------|
| [py3dvision](https://github.com/csiro/cvmiam-py3dvision) | a core 3D reconstruction library written in Python and completely independent of ROS2. Contains tests and example applications as well. |
| [py3dvision_interfaces](https://github.com/csiro/cvmiam-py3dvision_interfaces) | ROS2 communication interfaces required by py3dvision_ros nodes. |
| [py3dvision_ros](https://github.com/csiro/cvmiam-py3dvision_ros) | ROS2 wrappers for most of py3dvision functionality it injects py3dvision as a submodule. |
| [kinfu_zivid](https://github.com/csiro/cvmiam-ros2_kinfu_zivid) |	Fuses depth images to do 3D reconstruction with or without noise filtering using Zivid/Kinect's noise model. |
| [ros2_kinfu_zivid](https://github.com/csiro/cvmiam-ros2_kinfu_zivid) | Ros 2 wrapper for kinfu_zivid package. |
