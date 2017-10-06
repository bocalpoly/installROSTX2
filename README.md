# installROSTX2
Install Robot Operating System (ROS) on NVIDIA Jetson TX2

These scripts will install Robot Operating System (ROS) on the NVIDIA Jetson TX2 development kit.

Tested on L4T 27.1

The script is based on the Ubuntu ARM install of ROS Kinetic: http://wiki.ros.org/kinetic/Installation/UbuntuARM

Maintainer of ARM builds for ROS is http://answers.ros.org/users/1034/ahendrix/

<strong>updateRepositories.sh</strong>
This is an optional step. Adds the repositories universe, multiverse, and restricted and then apt-get update. These repositories are in the standard 27.1 install, so probably not needed.

1.	Use installROSTX2
2.	Git clone the url 
Get clone https://github.com/bocalpoly/installROSTX2.git
3.	Run the installation 
cd installROSTX2 
ls
./installROS.sh
4.	Setup the workspace, he default workspace name is catkin_ws. This script also sets up some ROS environment variables. Refer to the script for details.
./setupCatkinWorkspace.sh MAGI   
5.	Double check roscore
6.	Rosnode list
