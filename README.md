# Project: Bundled Openmanipulator-X ROS2 Humble Dependencies for Simulation in Gazebo Ignition (Fortress)

This repository bundles together specific versions of several GitHub projects that are required for our ROS2-based manipulator project.
The purpose of this bundling is to ensure compatibility across all dependencies, as the project only works with these exact versions. 

## Usage

To set up your environment and run the OpenManipulator in Gazebo Fortress with ROS Humble, follow these steps:

1. Clone this bundled repository:
   ```bash
   git clone https://github.com/robertik10/Openmanipulator_Gazebo_Humble_Dependencies.git>
   ```

2. Clone the required forks from the ROBOTIS repository:
  - OpenManipulator Package
    ```bash
     git clone https://github.com/robertik10/open_manipulator_humble_gazebo_fortress.git
     ```

  - OpenManipulator Simulations Package
    ```bash
    git clone https://github.com/robertik10/open_manipulator_humble_gazebo_fortress_simulations.git
    ```

These forks are the main packages needed to run the OpenManipulator in Gazebo Fortress with ROS Humble.
Note that the control of the robot is currently limited to joint manipulation and reading the joint outputs, as well as the end effector position.

For more detailled information on correct usage and installation as well as documentation, you can check out [this wiki page](https://zircon-november-c5e.notion.site/OpenManipulator-X-Gazebo-ROS-2-5a1453a05e344a70801a072e3aa61015?pvs=4).

## Included Dependencies

The following GitHub projects are bundled in this repository, each pinned to a specific branch to ensure compatibility:

1. **Dynamixel Workbench**
   - Repository: [ROBOTIS-GIT/dynamixel-workbench](https://github.com/ROBOTIS-GIT/dynamixel-workbench)
   - Branch: `ros2`

2. **gz_ros2_control**
   - Repository: [ros-controls/gz_ros2_control](https://github.com/ros-controls/gz_ros2_control)
   - Branch: `humble`

3. **Open Manipulator Messages**
   - Repository: [ROBOTIS-GIT/open_manipulator_msgs](https://github.com/ROBOTIS-GIT/open_manipulator_msgs)
   - Branch: `ros2`

4. **Open Manipulator Dependencies**
   - Repository: [ROBOTIS-GIT/open_manipulator_dependencies](https://github.com/ROBOTIS-GIT/open_manipulator_dependencies)
   - Branch: `ros2`

5. **ROBOTIS Manipulator**
   - Repository: [ROBOTIS-GIT/robotis_manipulator](https://github.com/ROBOTIS-GIT/robotis_manipulator)
   - Branch: `ros2`

## Purpose

The specific versions of these dependencies are crucial to the proper functioning of our ROS2 manipulator project.
By bundling them together in this repository, we ensure that the environment remains consistent, avoiding potential issues that might arise from version mismatches.

## Acknowledgments

We would like to acknowledge the hard work of the maintainers and contributors of the following projects:

- [ROBOTIS-GIT/dynamixel-workbench](https://github.com/ROBOTIS-GIT/dynamixel-workbench)
- [ros-controls/gz_ros2_control](https://github.com/ros-controls/gz_ros2_control)
- [ROBOTIS-GIT/open_manipulator_msgs](https://github.com/ROBOTIS-GIT/open_manipulator_msgs)
- [ROBOTIS-GIT/open_manipulator_dependencies](https://github.com/ROBOTIS-GIT/open_manipulator_dependencies)
- [ROBOTIS-GIT/robotis_manipulator](https://github.com/ROBOTIS-GIT/robotis_manipulator)

These projects form the backbone of our work, and we are grateful for their continued development and support.
