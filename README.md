# DynamicConv2D-Image-ResAttentionNet
The pytorch implementation of DynamicConv2D-Image-ResAttentionNet for Deep Learning Assignment II in NCKU.

[[Assignment]](https://drive.google.com/file/d/1FPvsmi0XM7ZKvXwllA18ZR_OHrxDfMEb/view?usp=sharing) [[Report]](https://drive.google.com/file/d/1xlsdUXurWLtfQUzLi5ErF3g7WTOKmZJD/view?usp=sharing)

# Files Description

`DL_Assignment2_1.ipynb`: Task1 executable file

`DL_Assignment2_2.ipynb`: Task2 executable file

`DL_visualization.ipynb`: Drawing executable

# Task1 - Designing a Convolution Module for Variable Input Channels

Design a special convolutional module that is spatial size invariant and can handle an arbitrary number of input channels. You only need to design this special module, not every layer of the CNN. After designing, explain the design principles, references, additional costs (such as FLOPS or #PARAMS), and compare with naive models. To simulate the practicality of your method, use the ImageNet-mini dataset for training, and during the inference process, test images with various channel combinations (such as RGB, RG, GB, R, G, B, etc.) and compare the performance.

## ResNet18(DynmicConv2D)
<img src="fig/ResNet18(DynamicConv2D)_loss_accuracy_Plots.png" width="700"/> 

## ResNet18
<img src="fig/ResNet18_loss_accuracy_Plots.png" width="700"/>


# Task2 - Designing a Convolution Module for Variable Input Channels

Design a (2-4)-layer CNN, Transformer, or RNN network that can achieve 90% performance of ResNet34 on ImageNet-mini (i.e., with no more than 10% performance loss). There are no restrictions on parameter count or FLOPS, but the maximum number of input and output layers is limited to 4-6. Explain the design principles, references, and provide experimental results. We suggest you DO NOT use pre-trained models for ResNet34.

## 3-layer ResAttentionNet
<img src="fig/ResAttentionNet_loss_accuracy_Plots.png" width="700"/> 

## ResNet34
<img src="fig/ResNet34_loss_accuracy_Plots.png" width="700"/> 




# Contact

If you have any question, please feel free to contact the author via [lres50804@gmail.com].
