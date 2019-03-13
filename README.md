# loam_velodyne
loam algorithm for hesai lidar p40p

## How to build with catkin

```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/YaleCheung/loamForHesai.git
$ cd ~/catkin_ws
$ catkin_make -DCMAKE_BUILD_TYPE=Release 
$ source ~/catkin_ws/devel/setup.bash
```

## Running

```
roslaunch loam_velodyne loam_velodyne.launch
```

## Hesai
```
roslaunch hesai_lidar p40p.launch pcap_file:=filename
```

