# raspisim_lefthand
---
## 概要
***作成中です***
[シミュレータ上のラズパイマウスを動かす方法 Part5]https://raspimouse-sim-tutorial.gitbook.io/project/tutorial/how_to_control_raspimouse_on_sim_5)
のPythonサンプルソースをC++で書きなおしたものです

## environment
* ubuntu 16.04LTE
* gazebo 9.0
* c 11
* ros kinetic 

## require
1. clone packages
    * raspi_ros_2
    * raspi_sim_tutorial
    * this repo
```
git clone ...
git clone ...
git clone ...
```

## quick_start
```
cd ...PATH_TO_THIS_FOLDER
catkin bt
roslaunch lefthand lefthand_with_samplemaze.launch
```

## Folder
### include
header file
### launch
* lefthand.launch
* lefthand_with_samplemaze.launch
### src
* main.cpp
* lefthand.cpp