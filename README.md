# -ros_gazebo_car_camera_yolo
 ros_gazebo_car_camera_yolo

详细的过程我写在了博客里：
https://blog.csdn.net/WhiffeYF/article/details/109187804

运行的命令：

启动gazebo中小车和摄像头的仿真： roslaunch mrobot_gazebo my_gazebo3.launch

启动yolo检测：roslaunch darknet_ros darknet_ros.launch

启动键盘控制小车：roslaunch mrobot_teleop mrobot_teleop.launch


