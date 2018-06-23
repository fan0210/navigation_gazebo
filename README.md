# navigation_gazebo
A ros navigation(mapping) simulation demo in gazebo

## Building project
### 1.Prerequisites
* [ROS Kinetic](http://wiki.ros.org/ROS/Installation)
* [gazebo](http://gazebosim.org/)

### 2.Create a workspace and compile
`mkdir -p ~/catkin_ws/src`<br>

next, copy these two files to `/catkin_ws/src` and<br>

`catkin_make`<br>

## Usage 
  * `roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch`
  
  * `roslaunch navigation navigation.launch`
  
## Show result

* **gazebo**

![image1 load error]()<br>

* **rviz**

![image2 load error]()<br>
