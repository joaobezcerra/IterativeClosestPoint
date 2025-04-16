# 3D Trajectory Estimation using ICP Algorithm

![3D Trajectory Visualization](https://via.placeholder.com/800x400.png?text=3D+Trajectory+Comparison)

This project implements the Iterative Closest Point (ICP) algorithm to estimate 3D trajectories from sequential LiDAR point clouds, with validation against ground truth data.

## Features

- Complete ICP implementation with SVD-based rigid transformation
- 3D trajectory reconstruction from point cloud sequences
- Visualization of estimated vs ground truth trajectories
- Error metric calculation (MSE)
- Optimized with KD-trees and point cloud downsampling

## Requirements

- Python 3.6+
- Required packages:
  ```bash
  numpy matplotlib trimesh scipy tqdm

### Docs

- Image classification
  - VGG, ResNET
- [Object detection](https://viso.ai/deep-learning/object-detection/) 
  - Two stage models (R-CNN, Fast R-CNN, Faster R-CNN)
  - One stage models  (YOLO, SSD)
  - [Vision Transformer (ViT)](https://viso.ai/deep-learning/vision-transformer-vit/)
  - NMS algorithm 
- Object Tracking
