Build workspace

  git clone https://github.com/PluemW/project_robo.git

Next

  cd project_robo
  
  colcon build
  
  source ~/.bashrc or source /install/local_setup.bash

Launch Command 

  ros2 launch articubot_one sim.launch.py

Teleop_keyboard Command

  ros2 run articubot_one teleop_twist_keyboard.py
