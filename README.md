# This is the lab3nav package

## Luca Ciampaglia

## Use the launch file lab3display.launch to launch the rosbag playback, rviz viewer with the relevant map config file, and the xacro/urdf robot file.

```roslaunch lab3nav lab3display.launch bag_file:=  map_file:= rviz_config:=```
The args `bag_file` and `map_file` both should be the relevant bag or map files. If left blank, they default to searching for ros_bag_data and maps_glennan, respectively.
The arg ``rviz_config`` should be either lab3laserconfig.rviz or lab3mapconfig.rviz.

This also depends on an updated lab 2 launch file and the glennan5 map launch file in order for certain passed arguments to function properly.





