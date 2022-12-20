# ROS Noetic containers for Jetson


To run a container use the container script

|                                   | L4T Version  | Container Tag                                  |
|-----------------------------------|:------------:|------------------------------------------------|
| ROS Noetic with Mavros            | r35.1.0      | duanenielsen/ros:noetic-ros-mavros-l4t-r35.1.0 |

to build

```
sudo docker build noetic/mavros/ -t duanenielsen/ros:noetic-ros-mavros-l4t-r35.1.0
```

to run 

```
./scripts/docker_run -c duanenielsen/ros:noetic-ros-mavros-l4t-r35.1.0
```
