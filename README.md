### About
Haptic workspace provides a platform for simulating your physical systems.
Workspace has integrated two haptic devices, which can be used for controlling the objects in the workspace.
It was created for implementing robot-assisted upper-limb bi-manual rehabilitation exercises. Workspace can be incorporated with other objects based on the exercise.
It provides a physics-based environment that provides humans with a real feel of working in a real space.

# Steps to configure

### clone the package to your home

```
cd
git clone https://github.com/Avi241/haptic_ws
```

### compile and source the package 

```
cd ~/haptic_ws
catkin_make
source devel/setup.bash
```

### Run the simulation assuming that both the falcon are connected first left then right is connected 

```
roslaunch haptic_pkg box_with_falcon.launch
```

### The main control script is box_with_falcon.py which is localted at  ~/haptic_ws/src/haptic_pkg/scripts . Edit this script according to you and run using the below command in new terminal



```
cd ~/haptic_ws
source devel/setup.bash
rosrun haptic_pkg box_with_falcon.py

```
## Demonstration
```
The video of the bi-manual rehabilitation task that was performed at our Lab is available here:
https://drive.google.com/file/d/1-LyKFd3FtbXIei6z_SiwLqro4fwmLbXC/view?usp=sharing
(Experiment without robot assistance(0:1.23)
Assist-as-needed rehabilitation(1.23:2.28) ) 
```
