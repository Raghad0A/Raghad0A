# Arm package
```git clone https://github.com/smart-methods/arduino_robot_arm.git```
## catkin folder
```cd ~/catkin_ws```
### some fo insructions from ros
```rosdep install --from-paths src --ignore-src -r -y```

```sudo apt-get install ros-kinetic-moveit```

```sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui```

```sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher```

```sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control```

```sudo nano ~/.bashrc```

## at the end of the (bashrc) file add the follwing line
(source /home/wesam/catkin_ws/devel/setup.bash)
## then 
ctrl + o
ctrl+ x
```source ~/.bashrc```

```roslaunch robot_arm_pkg check_motors.launch```

![](images/![2022-07-27](https://user-images.githubusercontent.com/108229514/181123964-8ac7f06a-20ce-495c-98ae-3a4a5adde8f6.png)
