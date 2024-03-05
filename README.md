# ROS2_SITL_offb_example

터미널1

MicroXRCEAgent udp4 -p 8888

터미널2

cd PX4-Autopilot

터미널3

cd ~/ws_sensor_combined/
ros2 launch px4_ros_com sensor_combined_listener.launch.py

터미널4

cd ~/ws_offboard_control/src/
ros2 run px4_ros_com offboard_control
