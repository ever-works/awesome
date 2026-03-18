## Overview

Awesome 3D LiDAR Datasets collects publicly available LiDAR datasets for research in autonomous driving, robotics, and 3D scene understanding.

## Autonomous Driving Datasets

### KITTI
Pioneer autonomous driving dataset:
- Velodyne 64-line LiDAR
- Camera images
- GPS/IMU data
- 3D object annotations
- Multiple tasks (detection, tracking, segmentation)

### nuScenes
Large-scale autonomous driving:
- 1000 scenes, 20 seconds each
- Full 360-degree coverage
- 6 cameras
- 5 radars
- 1 LiDAR
- 3D bounding boxes
- Tracking IDs

### Waymo Open Dataset
Large and diverse:
- 1,000 segments of driving data
- High-resolution LiDAR
- 5 LiDAR sensors
- Multiple cameras
- 12M 3D labels

### Argoverse
Two versions for different tasks:
- Motion forecasting
- 3D tracking
- HD maps
- Multiple cities

## Urban/Outdoor Datasets

### SemanticKITTI
Semantic segmentation:
- Built on KITTI
- Point-wise labels
- 28 classes
- Sequential data

### Toronto-3D
Urban outdoor dataset:
- Mobile LiDAR
- Point-wise labels
- 8 object classes
- Large-scale coverage

### SensatUrban
Urban photogrammetry:
- Aerial and mobile acquisition
- Dense point clouds
- 13 semantic classes

## Indoor Datasets

### Stanford 2D-3D-S
Indoor spaces:
- RGB-D and LiDAR
- Semantic annotations
- Multiple modalities

### ScanNet
RGB-D indoor dataset:
- 1,513 scans
- Semantic voxel labels
- Camera poses

## Specialized Datasets

### Forest/Vegetation
- TreeLS data
- Forest inventory
- Individual tree detection

### Infrastructure
- Bridge inspection
- Tunnel mapping
- Power line detection

## Common Tasks

- 3D object detection
- Semantic segmentation
- Instance segmentation
- 3D tracking
- Odometry/SLAM
- HD map creation

## Evaluation Metrics

- 3D IoU
- Average Precision (AP)
- Mean Average Precision (mAP)
- Segmentation accuracy
- Tracking metrics (MOTA, MOTP)