### (This fork has some remapping and change of parameters in the launch files)

RPLIDAR ROS package
=====================================================================

ROS node and test application for RPLIDAR

Visit following Website for more details about RPLIDAR:

rplidar roswiki: http://wiki.ros.org/rplidar

rplidar HomePage:   http://www.slamtec.com/en/Lidar

rplidar SDK: https://github.com/Slamtec/rplidar_sdk

rplidar Tutorial:  https://github.com/robopeak/rplidar_ros/wiki

How to build rplidar ros package
=====================================================================

1) Clone this project to your colcon workspace src folder
```
git clone <repository-name>
```
2) Install Eloquent ROS2 and colcon compiler.


```
cd [your-ros-package-directory]/src

git clone <repository>

cd [your-ros-package-directory]

colcon build --symlink-install

source ./install/setup.bash
```

Check if package exists

```
ros2 pkg list | grep rplidar
```

Start RPLIDAR
------------------------------------------------------------

```
ros2 launch rplidar_ros rplidar.launch.py
```
