# demo_lidar


# Setup instructions

Ensure you are on ROS-Indigo which supports OpenCV 2 out of the box.

```
sudo apt-get install libsuitesparse-dev libeigen3-dev libsdl1.2-dev
cd ~/catkin_ws/src
git clone <link>
cd ..
catkin_make
```
# Run instructions
1) Download bag files from here: 
http://www.frc.ri.cmu.edu/~jizhang03/Datasets/nsh_west_no_IMU.bag

Run the following in two terminals:
`roslaunch demo_lidar demo_lidar.launch`

cd to the directory where bag file is stored. The -l option makes it loop:
`rosbag play -l nsh_west_no_IMU.bag`
