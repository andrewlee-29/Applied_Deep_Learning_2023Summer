# Dilated CNN model for Image Classification

## Introduction

        Convolution neural network (CNN) is a popular method on image classification, and there are different researches to try to improve the perfromance of CNN. Commonly, CNN layer use the convolutions kernal to output feature map. [1] stated dilated convolution kernels is able to improve the image classification performance. The objective of the project is to test and compare the result of traditional CNN, dilated CNN, and hybrid dilated CNN (HDC) with my own implementation.

## Literature Review

        [1] mentions there are many researches focusing on improving image classification methods and increasing the accuracy, and the consumption of computing resources and the reduction of efficiency cannot be overlooked. The researchers propose the dilated convolution kernel can improve the image classification performance without increasing the complexity. Dilated convolution is generally used in image semantic segmentation. It expands the convolution kernel by inserting holes between its consecutive elements. The researchers implement three types of models: traditional CNN (CNN with traditional convolution kernels), dilated CNN(CNN with dilated convolution kernels and same dilation rates), and HDC model(hybrid dilated CNN, CNN with dilated convolution kernels and different dilation rates). As a result, dilated CNN model and HDC model have obvious time required improvement compared with traditional CNN model and HDC models also have highest accuracy. The dilated CNN models have the same accuracy as traditional CNN models and researchers provided two reasons for this. One reason is the dilated convolution kernel causes the loss of the pixel that contains continuity information. Second reason is the fixed kernel size rate causing the large and small size information cannot be taken into account simultaneously when extracting the image feature map.

## Implementation/ Method

## Results

## REFERENCES

    [1]. X. Lei, H. Pan and X. Huang, "A Dilated CNN Model for Image Classification," in IEEE Access, vol. 7, pp. 124087-124095, 2019, doi: 10.1109/ACCESS.2019.2927169.
