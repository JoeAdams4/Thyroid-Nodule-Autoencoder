# Thyroid Nodule Autoencoder

### Abstract

Thyroid nodules are an extremely common occurrences in adults though only a small portion of these nodules are malignant.. Fine Needle Aspiration (FNA) biopsies are commonly performed to identify malignancy and there is a pressing need for reliable, non-invasive methods to reduce unnecessary FNA procedures. In this study, we explore different architectures of one class autoencoders as a means to make this classification from a dataset of 964 Shear Wave Elastography and B-mode ultrasound images. The different autoencoders were constructed with varying numbers of layers and layer depths and were trained to encode and reconstruct images of benign nodules only. The intention is that images of benign nodules will have a lower reconstruction error than malignant nodules. This reconstruction error can then be used as the test statistic to classify images. The success of each autoencoder was evaluated using the area under a curve (AUC) and accuracy of classification.  The highest AUC achieved was 0.872, with an accuracy of 88.2% for the determination of malignancy. This study demonstrates that autoencoders offer a viable approach for thyroid nodule classification on ultrasound images.  

### Introduction
Thyroid nodules, are solid fluid filled growths that are extremely common. There are many different causes of thyroid nodules, and they are very rarely serious. However, thyroid nodules do have the potential to be cancerous. Currently, the main method of testing the nodules is a fine needle aspiration biopsy. In this procedure, a needle will be instered into the paitents thyroid using ultrasound guidance. The needle will then collect samples of cells from the thyroid to be tested. This is usually repeated 2-6 times to increase the liklihood that any cancerous cells will be found. This procedure, while relatively simple, is quite painful for the patient, and consumes hospital resources. Given the commonality of thyroid nodules, and the rarity that they are cancerous, there is demand for an effient, reliable, and non-invasive alternative that could potentially reccomend patients with particularly suspicious nodules for an FNA biopsy, while filtering out patients with benign nodules. This would help mitigate the amount of unneccesary FNA procedures, therefore saving hospital resources and patients' necks. Machine learning algorithms offer a variety of approaches to build a tool to make thyroid nodule classifications. One such approach is to use an autoencoder.

### Methods

Three autoencoders with different structures were used to classify the nodules. An autoencoder is a type of neural network that uses convolutional layers to encode and identify key features of input images, then decodes and reconstructs the image. The mean squared error (MSE) between the input and output image is used to quantify reconstruction error. The nodautoencoders were trained using only images of benign thyroid nodules. When the autoencoders receive a malignant nodule image, the MSE will be higher. The MSE can be used to classify the image.

### Results

The AUC (area under curve) of a ROC curve is used to measure the performance of the autoencoders with the best possible score of 1. The autoencoders all achieved respectable scores the most successful being the medium sized architecture achieving an AUC of 0.875, an accuracy of 0.87, and a specificity of 0.47 at 95%.

### Discussion

