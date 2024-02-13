# 3D motion tracking using multiple cameras with OpenPose and Pose2Sim

This repository provides a workflow for motion tracking from multiple cameras using OpenPose, and subsequent triangulation of 2D coordinates using pose2sim. The 3D coordinates can be used, for instance, in OpenSim that allows for extraction of full-body 3D joint angles.

# Folders
-- Images = Some images and temporary video folder
-- openpose = OpenPose materials, see inside (You need to seperately download bin and models!)
-- Pose2Sim = pose2sim projects files
-- projectdata = each folder within projectdata contains a trial or seperate scene, containing calibration folder, and raw 2D videos (then folders are added as you run the code)
-- User = some logging that pose2sim does for archiving output during running of code

## Scripts
openpose_to_pose2sim_tracking.ipynb = main jupyter notebook script to run the envision demo

## Pre-reqs (install these packages)
requirements.txt 

# Was this helpful?

citation for this module: Kadavá, S., Pouw, W. (2024). 3D motion tracking using multiple cameras with OpenPose and Pose2Sim [the day you viewed the site]. Retrieved from: xxx

# Contact

sarka.kadava@donders.ru.nl