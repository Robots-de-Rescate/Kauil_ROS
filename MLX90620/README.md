Temperature sensor MLX90620
---------------------------

This directory contains all the ROS files for obtaining the sensor data from the microcontroller (Arduino MEGA) and for displaying the data in a graphic user interface.

**Files contained on the src directory**:

 - GUIMLX90620.py: once there is a publisher node running with the data being generated by the sensor in an int16 array format, this code creates a listener node for obtaining the data from the publisher and at the same time it is displayed on a GUI.


