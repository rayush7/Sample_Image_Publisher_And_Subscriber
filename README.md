# sample_image_publisher_and_subscriber (C++)
This repository contains code for publishing images captured by the webcam on the publisher node &amp; subscribing and then inverting them on the subscriber node.

ROS version: Indigo 

Opencv version : 3.1 

After cloning this repository in the same directory enter this command 

git clone https://github.com/ros-perception/vision_opencv.git (Indigo branch)

To build the package 

catkin_make 

To exectute the code 

roscore 

rosrun sample_image_publisher_and_subscriber my_webcam_publisher 0 

rosrun sample_image_publisher_and_subscriber my_webcam_subscriber 





