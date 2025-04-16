# 3D Trajectory Estimation using ICP Algorithm

This project implements the Iterative Closest Point (ICP) algorithm to estimate 3D trajectories from sequential LiDAR point clouds, with validation against ground truth data.

## Features

**ICP Pipeline**:
  - Point-to-point registration
  - SVD-based rigid transformation
  - KD-tree accelerated nearest neighbor search
  - 
**Trajectory Analysis**:
  - Sequential scan matching
  - Transformation chaining
  - 3D visualization with Matplotlib
    
**Performance**:
  - Point cloud downsampling
  - Convergence monitoring
  - MSE error metrics

## Requirements:

- Python 3.6+
- Required packages:
  ```bash
  numpy matplotlib trimesh scipy tqdm

## Dependencies:

numpy>=1.20
matplotlib>=3.5
trimesh>=3.9
scipy>=1.8
tqdm>=4.0

### Docs:

- [Object detection](https://viso.ai/deep-learning/object-detection/) 
- [Vision Transformer (ViT)](https://viso.ai/deep-learning/vision-transformer-vit/)

### References:

- KITTI Dataset: http://www.cvlibs.net/datasets/kitti/
- ICP Algorithm: Besl, P.J., McKay, N.D. (1992)
- https://pcl.readthedocs.io/projects/tutorials/en/master/iterative_closest_point.html
