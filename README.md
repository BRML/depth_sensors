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
|   +-- meshes/sensors/
|   +-- urdf/
|       +-- kinect/
|       +-- stand/
|
+-- senz3d_description/        URDF and meshes describing the Senz3d web camera
|   +-- meshes/sensors/
|   +-- urdf/
```
