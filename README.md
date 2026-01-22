# ResNet Architectural Analysis

This is my attempt at in-depth study of ResNet and how it solves the degradation of the network problem with incresing network depth of convolutional neural network. ResNet achieves this through short cut connections - feeding the input identity mapping to the final output of the network layers, essentially making the deeper layers of the model lern the change need to get to the target instead of creating a new target itself.

This notebook references the model developed by Rajarshi Banerjee
https://www.kaggle.com/code/banerz/resnet-implementation-in-pytorch
