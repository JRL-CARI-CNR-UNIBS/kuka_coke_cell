# Kuka coke cell

run gazebo, physics is paused by default
```
roslaunch kuka_coke_gazebo kr_50_r2500_gazebo_coke.launch
```


run moveit and cnr_ros_control
```
roslaunch kuka_coke_configurations simulation.launch gazebo:=true
```
it will unpause physics
