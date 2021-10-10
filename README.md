# ROS Multiple PC

This repository demonstrates how to connect multiple PC to a single ROS master.

- Main PC
  - export ROS_MASTER_URI=http://192.168.168.105:11311
  - export ROS_IP=192.168.168.105 # This is main PC ip address

- Second PC
  - export ROS_MASTER_URI=http://192.168.168.105:11311
  - export ROS_HOSTNAME=192.168.168.183 # This is second PC's ip address
