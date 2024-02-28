# Official implementation of 'MAFFN-SAT: 3D Point Cloud Defense via Multi-view Adaptive Feature Fusion and Smooth Adversarial Training'.
## Requirements

* Tensorflow>=1.14.0 (not support Tensorflow 2.0)  
* Pytorch>=1.2.0

## Compiling Cuda Operations
Please follow this [repo](https://github.com/charlesq34/pointnet2).

## Dataset
The ModelNet40 can be downloaded from [here](https://modelnet.cs.princeton.edu/).

## Training and Evaluating
Pretrained model used in the paper can be found in [here](https://drive.google.com/drive/folders/1JBYkdO2GlW_wKWvUXNDxrf8PQIJMuorN?usp=sharing). Or, you can train your own model from scratch. The attack code we used comes from [here].(https://github.com/GuanlinLee/CCNAMS)
```
python train.py
```
## Acknowledgment

We thank the authors of following works for opening source their excellent codes.  
* [PointNet/PointNet++](https://github.com/charlesq34/pointnet2), [DGCNN](https://github.com/WangYueFt/dgcnn)  
* [Perturb/Add attack](https://github.com/xiangchong1/3d-adv-pc), [Drop attack](https://github.com/tianzheng4/PointCloud-Saliency-Maps)  
* [CCN](https://github.com/GuanlinLee/CCNAMS)

We also thank the authors of related papers/repos for their inspiring discussions with us.
