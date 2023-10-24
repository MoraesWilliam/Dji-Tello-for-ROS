# Dji-Tello-for-ROS
application to implement ROS in a commercial drone such as DJI-Tello 

roscore
roslaunch rosbridge_server rosbridge_websocket.launch
roslaunch tello_driver tello_node_images.launch
rosrun scratch_example scratch_example.py
roslaunch orb_slam2_ros orb_slam2_d435_mono.launch
