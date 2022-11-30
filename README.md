This is the lab3nav package

Use the launch file lab3display.launch to launch the rosbag playback, rviz viewer with the relevant map config file, and the xacro/urdf robot file.

It has an argument for which config file to use, all options are located within the config folder, either lab3laserconfig.rviz or lab3mapconfig.rviz. If the map config is used, the argument use_map must be true in order for the map_server node to start and the argument for map size must be provided. 

This also depends on an updated lab 2 launch file and the glennan5 map launch file in order for certain passed arguments to function properly.





