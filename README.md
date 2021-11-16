# Deep Complex Networks
Project repository for the course of Neural Networks 2020, Sapienza University of Rome. 

The project has been developed by:
- Francesco Starna
- Gianmarco Bracalello

## Abstract
In recent years, research on deep learning models have been done using essentially techniques and architectures based on real-valued operations. From a mathematical point of view it is ensured that complex numbers have a richer representation. Despite the clear advantage on this, developing complex models has never taken hold, due to the absence of pre-built and stable models. In this paper we are going to present our solution, using Tensorflow, of the complex components, in order to build a complex-valued model. We also show that complex models can be applied in tasks such as image recognition and time series forecasting problems, obtaining competitive results.

## The project
The objective of this work is to extend the residual networks (ResNet) in the field of complex numbers following the paper [Trabelsi et al., 2017] on deep complex networks. In order to reach this goal each layer of the network has been customized to deal with complex inputs, and applied to the context of feed-forward convolutional networks. Specifically, the complex-valued layers we implemented are:
- Complex Batch Normalization
- Complex Weight Initialization
- Complex Convolution
- Complex ReLU-based activation functions
- Imaginary Learning Block
- Complex Dropout

Results on CIFAR10, CIFAR100 (images), Weather Dataset (time series forecasting) are written in the report. 

## [Presentation](https://github.com/Starnino/neural_networks_project/blob/main/Deep_Complex_Network_Presentation.pdf)
## [Report](https://github.com/Starnino/neural_networks_project/blob/main/Deep_Complex_Network_Report.pdf)
## [Notebook](https://github.com/Starnino/neural_networks_project/blob/main/Deep_Complex_Network.ipynb)

## References
> Chiheb Trabelsi and Olexa Bilaniuk and Ying Zhang and Dmitriy Serdyuk and Sandeep Subramanian and João Felipe Santos and Soroush Mehri and Negar Rostamzadeh and Yoshua Bengio and Christopher J Pal. 2017
[Deep Complex Networks](https://arxiv.org/pdf/1705.09792.pdf)
