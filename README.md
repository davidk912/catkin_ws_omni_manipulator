## Mobile manipulation
### 작성일자 : 01/06/22

# Gazebo 실행
cd ~/catkin_urdf_211020
catkin_make
source ~/catkin_urdf_211020/devel/setup.bash
roslaunch omni_manipulator_gazebo omni_manipulator_gazebo.launch

# manipulation 실행
cd ~/catkin_urdf_211020/src/omni_manipulator_control
python3 mobile_manipulation.py