Catkin 워크스페이스 빌드 방법:

```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/laboshinl/loam_velodyne.git
$ cd ~/catkin_ws
$ catkin_make -DCMAKE_BUILD_TYPE=Release 
$ source ~/catkin_ws/devel/setup.bash
```

실행:
```
roslaunch loam_velodyne loam_velodyne.launch
```
