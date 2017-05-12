## Usage

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