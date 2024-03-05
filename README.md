# ROS2_SITL_offb_example

터미널1

MicroXRCEAgent udp4 -p 8888

터미널2

cd PX4-Autopilot

make px4_sitl gazebo-classic

터미널3

cd ~/ws_offboard_control/src/

source /opt/ros/foxy/setup.bash

source install/local_setup.bash

ros2 run px4_ros_com offboard_control
