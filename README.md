## Neato Drivers

This repository contains the Neato ROS drivers, catkinized, and ready for ROS Hydro and newer.

## Usage
You can check this out into your catkin workspace as follows:

    cd <ws>/src
    git clone https://github.com/jlohse/neato_robot.git
    cd <ws>
    catkin_make
    source <ws>/devel/setup.bash

## Changes in this fork

 * The driver has been changed from the original version in order to support a wider range of neato models and firmware versions.
 * This node works with Indigo. The required third parameter to rospy.Publisher has been supplied.
 * A minor issue in xv11::setMotors() has been fixed. Due to incorrect indentation in that function neato used to slowly crawl forward.

