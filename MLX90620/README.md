![STM32_USB ROS node](https://github.com/Robots-de-Rescate/Kauil_ROS/blob/master/img/ROSNode_MLX90620.jpg)

This ROS node is not used at the moment in Kauil, because the code developed for obtaining the data from the temperature sensor was made for the arduino mega and kauil only has the STM32 micrcontroller to send data to ROS. This is the reason why this is a proyect exlplained at the general wiki. 

This directory contains all the ROS files for obtaining the temperature sensor data (MLX90620) from the microcontroller (Arduino MEGA) and for displaying the data in a graphic user interface.

Dependencies
-------
- rospy
- cpp (This dependency is not really needed for this package)

Function
------
 - GUIMLX90620.py: once there is a publisher node running with the data being generated by the sensor in an int16 array format, this code creates a listener node for obtaining the data from the publisher and at the same time it is displayed on a GUI.

![STM32_USB ROS node](https://github.com/Robots-de-Rescate/Kauil_ROS/blob/master/img/MLX90620_GUI.png)

Refer to the wiki for obtaining detail information and making this ROS node available to use in Kauil.
