# PID controller on Turtlesim
This package contains some experiments with Turtlesim which implement the classical PID controller for A to B motion and for pure turning in a differential drive mobile robot.

## 

## To Run the Code
For just listening to the Pose of the turtlesim, Run the following commands
```
roscore
rosrun turtlesim turtlesim_node
rosrun pid_turtle pid_turtle_pose_hear_node 
```
For moving to a Goal Pose given to the turtlesim bot, Run the following commands
```
roscore
rosrun turtlesim turtlesim_node
rosrun pid_turtle pid_turtle_pose_send_node 
```