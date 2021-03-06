<p align="left">
  <img src="images/logo.png" alt="torch_soft" />
  <br />
  <br />
  <img src="https://img.shields.io/badge/version-0.1.1-blue.svg" alt="Version">
  <a href="https://github.com/shan18/TensorNet/blob/master/LICENSE"><img src="https://img.shields.io/apm/l/atomic-design-ui.svg?" alt="MIT License"></a>
  <br />
</p>

torch_soft is a high level implementation of pytorch for some of claasification implementation with ease...

## Installation

You can use pip to install torch_soft using pip.

```[bash]
pip install torch-soft==0.1.1
```

## features
TensorNet currently supports the following features
- Model architectures
  - ResNet18
  - A custom model called naiveresnet
- Model utilities
  - Loss functions
    - Cross entropy loss
    - nll_loss
  - Optimizers
    - Stochastic Gradient Descent
  - Regularizers
    - L1 regularization
    - L2 regularization
  - LR Schedulers
    - Step LR
    - Reduce LR on Plateau
    - One Cycle Policy
  - LR Range Test
- Model training and validation
- Datasets (data is is returned via data loaders)
  - MNIST
  - CIFAR10
  - TinyImageNet
- Data Augmentation
  - Resize
  - Padding
  - Random Crop
  - Horizontal Flip
  - Vertical Flip
  - Gaussian Blur
  - Random Rotation
  - CutOut
- GradCAM and GradCAM++ (Gradient-weighted Class Activation Map)
- Result Analysis Tools
  - Plotting changes in validation accuracy and loss during model training
  - Displaying correct and incorrect predictions of a trained model
  - Plotting images in a batch for visualization
  - Plotting gradcam outputs

## How to Use

For examples on how to use torch_soft, refer to the [examples](https://github.com/millermuttu/torch_soft/tree/master/examples) directory.

## Dependencies

torch_soft has the following third-party dependencies
- torch
- torchvision
- torchsummary
- tqdm
- matplotlib
- albumentations
- opencv-python
