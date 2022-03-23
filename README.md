# robot_a_config (Quaderpad with wheel)

it is just like a quaderpad which include wheels each legs has 2 degree of freedom to change the postion i used moveit configuration 

you can download this repository by fallowing bellow steps

cd catkin_ws/src
git clone https://github.com/Aravind8967/robot_a_config.git
cd ..
catkin_make

To see the robot command is 

roslaunch robot_a_bringup robot_a_bringup.launch

for slam and moveit operation ( in another terminal type)

roslaunch robot_a_moveit_config robot_a_moveit_bringup.launch

these are the command to see

this robot has IMU joint, cmd_joints, lidar you can add the plugin and modify
