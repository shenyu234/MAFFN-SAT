# Official implementation of 'MAFFN-SAT: 3D Point Cloud Defense via Multi-view Adaptive Feature Fusion and Smooth Adversarial Training'.
## Requirements

Tensorflow>=1.14.0 (not support Tensorflow 2.0)  
Pytorch>=1.2.0

## Compiling Cuda Operations
Please follow this [repo](https://github.com/charlesq34/pointnet2).

## Dataset
The ModelNet40 can be downloaded from [here](https://modelnet.cs.princeton.edu/).

## Training and Evaluating
Pretrained model can be found in [here](https://drive.google.com/drive/folders/1JBYkdO2GlW_wKWvUXNDxrf8PQIJMuorN?usp=sharing). Or, you can train your own model from scratch.
```
python train.py
