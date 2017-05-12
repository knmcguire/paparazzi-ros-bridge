## Usage

- Install to workspace:
```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone XXX
```

- Build
```
cd ~/catkin_ws
catkin_make
```
If required, add the hector source to this workspace:
```
cd ~/catkin_ws/src
ln -s /path/to/hector/src hector_src
```

- Source workspace
```
source devel/setup.bash
```


- Launch
```
roslaunch paparazzi_ros_template_project main.launch
```