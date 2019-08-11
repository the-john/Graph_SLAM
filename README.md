# Graph_SLAM
# Landmark Detection & Robot Tracking (SLAM)

## Project Overview
In this project, I've implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! I've combined what I know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.l

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in this work I generated a variety of these maps.

!(robot_world)[https://github.com/the-john/Graph_SLAM/blob/master/images/robot_world.png]

Example of SLAM output (estimated final robot pose and landmark locations).

## Project Instructions

The project is broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures, Notebook 3 is where all the real action takes place:

Notebook 1 : Robot Moving and Sensing

Notebook 2 : Omega and Xi, Constraints

Notebook 3 : Landmark Detection and Tracking

**You can find these notebooks in this github repository.** 
