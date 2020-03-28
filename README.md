# DJI-Tello-Autonomous-Flight
This is a program which uses the haar cascades from OpenCV to detect a human in fron tof the drone and adjust its flight according to the distance to it.
The video feed from the front camera of the drone is taken and a bounding box is created around the detected face. A target spot is created at the center of this bounding box. Then control signals are given through a pygame window to the drone to adjust its position according to this target spot. This method is only possible thanks to the Tello's incredible stability. It won't work well in windy conditions so try and fly it indoors.

DJI Tello: https://store.dji.com/product/tello?vid=38421
