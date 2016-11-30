# depth_sensors
URDF and meshes describing the Kinect V2 and Senz3d depth sensors for use 
with ROS and Gazebo.

ROS metapackage containing packages describing and controlling the Kinect V2
and the Senz3d depth sensors.

## depth_sensors repository structure
```shell
.
|
+-- depth_sensors/             depth_sensors metapackage
|
+-- kinect_control/            joint state controller for Kinect stand
|   +-- config/
|
+-- kinect_description/        URDF and meshes describing the Kinect sensor and the stand
|   +-- launch/
|   +-- meshes/sensors/
|   +-- urdf/
|       +-- kinect/
|       +-- stand/
|
+-- senz3d_description/        URDF and meshes describing the Senz3d web camera
|   +-- meshes/sensors/
|   +-- urdf/
```

The sensor meshes (.dae files) and visualizations (.jpg and .png files) have been obtained from the [`turtlebot_description` package](https://github.com/turtlebot/turtlebot/tree/kinetic/turtlebot_description). 
