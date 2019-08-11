# Graph_SLAM
# Landmark Detection & Robot Tracking (SLAM)

## Project Overview
In this project, I've implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! I've combined what I know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems.l

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using only sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in this work I generated a variety of these maps.

!()[]

Example of SLAM output (estimated final robot pose and landmark locations).
Project Instructions
The project will be broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures, only Notebook 3 and the robot_class.py file will be graded:
Notebook 1 : Robot Moving and Sensing
Notebook 2 : Omega and Xi, Constraints
Notebook 3 : Landmark Detection and Tracking
You can find these notebooks in the Udacity workspace that appears in the concept titled Project: Landmark Detection & Tracking. This workspace provides a Jupyter notebook server directly in your browser.
You can also choose to complete this project in your own local repository, and you can find all of the project files in this GitHub repository. Note that while you are allowed to complete this project on your local computer, you are strongly encouraged to complete the project from the workspace.
Evaluation
Your project will be reviewed by a Udacity reviewer against the Landmark Detection & Tracking project rubric. Review this rubric thoroughly, and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.
Zip file submission
If you are submitting this project from a workspace or as a zip file, it is recommended that you follow the instructions in the final workspace notebook to compress your project files and make sure your submission is not too large. You are only graded on Notebook 3, and the file robot_class.py.
