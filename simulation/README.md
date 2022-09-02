# How to run simulation


kobuki_gazebo, kobuki_desctipotion 

`$CATKIN_PATH/kobuki/kobuki_description/urdf` 폴더에 저장

* kobuki.urdf.xacro
* kobuki_gazebo.urdf.xacro
* rplidar.dae


`$CATKIN_PATH/kobuki_desktop/kobuki_gazebo/launch` 폴더에 저장

* kobuki_library.launch 

`$CATKIN_PATH/kobuki_desktop/kobuki_gazebo/worlds` 폴더에 저장

* library.world 
catkin_make 진행

---

### 실행 방법

1. roslaunch kobuki_gazebo kobuki_library.launch
