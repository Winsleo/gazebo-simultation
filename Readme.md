To run the simulation:
```bash
$ roslaunch scout_gazebo gazebo.launch
```
There are three kinds of lidars in the package。You can use argument `lidar_type` in `scout_gazebo/urdf/base.xacro`to choose the lidar type：:
- 0 : 360° spinning lidar
![360° spinning lidar](scout_gazebo/meshes/velodyne.png)
- 1 : livox lidar
![livox lidar](scout_gazebo/meshes/livox.png)
- 2 : small FOV solid lidar
![small FOV solid lidar](scout_gazebo/meshes/solid.png)




