cd ~/ros2_ws

colcon build --packages-select sketch_bot_moveit_config

source install/setup.bash
 or 
source ~/.bashrc

cd src/sketch_bot_moveit_config

ros2 launch sketch_bot_moveit_config demo.launch.py

Rviz 가 실행되면 
Add -> RobotModel
Add -> TF