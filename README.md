# 3D MOTION TRACKING WITH POSE2SIM

This repository provides a workflow for motion tracking from multiple cameras using OpenPose, and subsequent triangulation of 2D coordinates using pose2sim. The 3D coordinates can be used, for instance, in OpenSim that allows for extraction of full-body 3D joint angles.

## Installation

1. Install OpenPose
2. Install Pose2Sim

## Folder structure

<pre>
pose2sim
videodata         
├── trial_0 
    ├── calibration
        ├── cam1
        ├── cam2
        └── cam3
    └── raw-2d
├── trial_1 
└── trial_2
</pre>

Folder `pose2sim` contains your installed model and an empty folder with the project structure.

Folder `videodata` contains trial-sized videos in separate folders. Each trial folder includes `raw-2d` folder where you store the videos from multiple cameras. The XXX offers a script that cuts multiple-camera video to separate views and distribute it to folders that align with this structure.

Folder `calibration` contains calibration videos from multiple cameras, each in separate folder. If all your videos are tied to one calibration, you need to place the calibration folder only in the first folder of your trials. If there are multiple calibration setups, place calibration folder with videos to each first trial folder for the respective setup.