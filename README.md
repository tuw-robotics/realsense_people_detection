based on https://github.com/IntelRealSense/realsense_samples_ros

## Dependencies 

### Intel RealSense SDK for Linux
```
sudo apt-key adv --keyserver keys.gnupg.net --recv-key D6FB2970   
sudo sh -c 'echo "deb http://realsense-alm-public.s3.amazonaws.com/apt-repo xenial main" > /etc/apt/sources.list.d/realsense-latest.list'  
sudo apt update 
sudo apt install -y librealsense-object-recognition-dev librealsense-persontracking-dev librealsense-slam-dev libopencv-dev
```

### ROS dependencies
* [tuw_common](https://github.com/tuw-robotics/tuw_common) ```check the INSTALL.md inside the pkg because it holds submodules```
  * [tuw_msgs](https://github.com/tuw-robotics/tuw_msgs)

## Camera Driver
```
sudo apt install ros-kinetic-realsense-camera  
```
launch file included here  
http://wiki.ros.org/realsense_camera  
