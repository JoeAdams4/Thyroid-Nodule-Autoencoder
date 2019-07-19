## Thydoid Nodule Classification Using an  Autoencoder

### Abstract

Thyroid nodules are an extremely common occurrences in adults though only a small portion of these nodules are malignant.. Fine Needle Aspiration (FNA) biopsies are commonly performed to identify malignancy and there is a pressing need for reliable, non-invasive methods to reduce unnecessary FNA procedures. In this study, we explore different architectures of one class autoencoders as a means to make this classification from a dataset of 964 Shear Wave Elastography and B-mode ultrasound images. The different autoencoders were constructed with varying numbers of layers and layer depths and were trained to encode and reconstruct images of benign nodules only. The intention is that images of benign nodules will have a lower reconstruction error than malignant nodules. This reconstruction error can then be used as the test statistic to classify images. The success of each autoencoder was evaluated using the area under a curve (AUC) and accuracy of classification.  The highest AUC achieved was 0.872, with an accuracy of 88.2% for the determination of malignancy. This study demonstrates that autoencoders offer a viable approach for thyroid nodule classification on ultrasound images.  

### Introduction
Thyroid nodules are extremely common in Adults. A very small portion of thyroid nodules are malignant. Fine Needle Aspirations biopsies are used to determine malignancy, and there is demand for a non-invasive, reliable classification method to reduce unnecessary FNAs.

### Methods

Three autoencoders with different structures were used to classify the nodules. An autoencoder is a type of neural network that uses convolutional layers to encode and identify key features of input images, then decodes and reconstructs the image. The mean squared error (MSE) between the input and output image is used to quantify reconstruction error. The autoencoders were trained using only images of benign thyroid nodules. When the autoencoders receive a malignant nodule image, the MSE will be higher. The MSE can be used to classify the image.

### Results

The AUC (area under curve) of a ROC curve is used to measure the performance of the autoencoders with the best possible score of 1. The autoencoders all achieved respectable scores from 0.825 – 0.875. 

### Discussion
