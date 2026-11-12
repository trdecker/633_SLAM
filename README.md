# 633_SLAM

A two part SLAM (Simultaneous Localization and Mapping) solution comprised ICP for LiDAR point clouds and Square Root SAM.

Utilizes the KITTI data set.

Group project for EC EN 633 Localization and Mapping in Robotics at Brigham Young University.
Fall 2026

## Project Description

## Frontend

ICP (Iterative Closest Point) performs SLAM on the KITTI data set. Passes transition and covariance matrices relevant for Square Root SAM to the backend.

## Backend

Square Root SAM (Smoothing and Mapping) for iteratively improving priors. Passes SAM result into frontend for performance improvement.

## Main Questions

- How much can an ICP LiDAR point cloud SLAM method estimate vehicle trajectories using LiDAR measurements alone?
- How much does a Square Root SAM-based system improve the accuracy of the original method.
- (Stretch goal): How much do camera and IMU measurements improve localization accuracy when incorporated into the model?

## Group Members
### Frontend
- Nick Smith
- Elijah Pettitt
- Tad Decker
### Backend
- Andema Mongane
- Adrian Ramirez
- Rowan Williams

