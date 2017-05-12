# Paparazzi / ROS bridge

This project is currently under development.

The Paparazzi / ROS bridge is a framework that allows Paparazzi modules for
tasks like visual navigation to be simulated in ROS + Gazebo using the Hector
quadrotor package. 

## Usage

- Install the hector quadrotor package

```
https://github.com/tu-darmstadt-ros-pkg/hector_quadrotor
```

- Install to workspace:

```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/tomvand/paparazzi-ros-bridge.git
```

- Build

First source hector workspace if req'd!

```
source ~/hector_ws/devel/setup.bash
```

Then build this workspace:

```
cd ~/catkin_ws
catkin_make
```

- Source this workspace

```
source devel/setup.bash
```


- Launch

```
roslaunch paparazzi_ros_template_project main.launch
```