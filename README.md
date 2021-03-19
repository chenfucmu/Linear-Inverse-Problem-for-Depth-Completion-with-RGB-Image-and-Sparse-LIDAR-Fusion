# Linear-Inverse-Problem-for-Depth-Completion-with-RGB-Image-and-Sparse-LIDAR-Fusion
## Paper


## Abstract
Modern high-definition LIDAR is expensive for commercial autonomous driving vehicles and small indoor robots. 
An affordable solution to this problem is fusion of planar LIDAR with RGB images to provide a similar level of perception capability. 
Even though state-of-the-art methods provide approaches to predict depth information from limited sensor input, they are usually a simple concatenation of sparse LIDAR features and dense RGB features through an end-to-end fusion architecture. 
In this paper, we introduce an inductive late-fusion block which better fuses different sensor modalities inspired by a probability model. 
The proposed demonstration and aggregation network propagates the mixed context and depth features to the prediction network and serves as a prior knowledge of the depth completion. 
This late-fusion block uses the dense context features to guide the depth prediction based on demonstrations by sparse depth features.
In addition to evaluating the proposed method on benchmark depth completion datasets including NYUDepthV2 and KITTI, we also test the proposed method on a simulated planar LIDAR dataset. 
Our method shows promising results compared to previous approaches on both the benchmark datasets and simulated dataset with various 3D densities.
