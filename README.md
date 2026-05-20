# knr_ros2_humanoid_virtual_twin
The repository contains ROS2 files to simulate Melman humanoid robot in Gazebo simulator. It also has files to run a real robot.

This repository uses Git submodules to manage external dependencies.

- [dynamixel_hardware](https://github.com/youtalk/dynamixel_hardware) 
- [dynamixel-workbench](https://github.com/ROBOTIS-GIT/dynamixel-workbench) 
- [dynamixel-workbench-msgs](https://github.com/ROBOTIS-GIT/dynamixel-workbench-msgs) 

Note: `gazebo_ros2_control` is managed as a system dependency.


### Cloning the repository

To download the repository along with all required submodules, use the following command:

```bash
git clone --recurse-submodules https://github.com/KNR-PW/LRT_ros2_humanoid_virtual_twin.git