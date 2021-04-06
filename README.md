# ColorTuner
## What is ColorTuner?

Colortuner component implements three different image color filters in the next color spaces: RGB, HSV, YUV. It is an application to configure tailored color filters in HSV, RGB, or YUV color spaces. It is use to obtain optimal values of tint and saturation, as well as lighting, in that kind of filters. 

This tool only has one thread who cares about getting images and showing them through the GUI. ColorTuner connects the ROS image publisher driver (real or simulated), images from it and each image is shown through an GUI class (called viewer').


<img src="/docs/assets/images/colortunerdocs.png" width="80%" height="60%">

Currently this tool is available in two branches:

1. ROS1 

It can be run used with Cameras and systems using ROS1 as middleware. To see how to use this tool visit the Installation and use page from the navigation bar.

## Local installation on Linux machines

The programming framework is composed of the ROS1 and ROS2 middleware, GtK based GUI and the JdeRobot base package. All this software is open source so there are alternative ways to install all of them directly from the source code. Currently we use ROS Melodic, ROS Dashing and JdeRobot-Academy (20180606) releases. Follow the <a href="/docs/_pages/installation.md">installation recipe</a> in the github repository to get the framework up and running, ready to use on your computer. 


