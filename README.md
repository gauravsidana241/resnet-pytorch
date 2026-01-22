# ResNet Architectural Analysis

This is my attempt at an in-depth study of ResNet and how it solves the network degradation problem associated with the increasing depth of convolutional neural networks. ResNet achieves this through shortcut connections—feeding the input identity mapping to the final output of the network layers, essentially forcing the deeper layers of the model to learn the change needed to reach the target instead of creating a new target representation.

This notebook references the model developed by Rajarshi Banerjee (https://www.kaggle.com/code/banerz/resnet-implementation-in-pytorch).
