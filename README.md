# Vision-detect-and-track
## 1. Descripción
The main  objective of this repository is to provide a set of computer vision tools to detect and track objects depending on their characteristics, but it was designed particularly to identify a soccer ball inside a soccer field. OpenCV in ROS was used to develop the algorithms. The tools implemented in the repository are:
* Kalman Filter + LBP Cascade
* Particle Filter + Color Detection
* Kalman Filter + Blob Color Detection
* SURF
* Dynamixel Servomotors Motion

![Image of kalman filter detection](https://github.com/marcovc41/vision-detect-and-track/blob/master/read_img/captura_1.png)

## 2. Requerimientos

#### Software

1. [ROS Kinetic Kame](http://wiki.ros.org/kinetic/Installation)
2. [OpenCV3 for ROS](http://wiki.ros.org/vision_opencv)
3. [Dynamixel libraries for ROS](https://github.com/aaceves/example_dynamixel)

    And if you want to train your own detection cascade:

4. [Computer Vision toolbox for MATLAB](https://www.mathworks.com/products/computer-vision.html)
