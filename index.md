## Thydoid Nodule Classification Using an  Autoencoder

### Abstract
	Thyroid nodules are an extremely common occurrences in adults though only a small portion of these nodules are malignant.. Fine Needle Aspiration (FNA) biopsies are commonly performed to identify malignancy and there is a pressing need for reliable, non-invasive methods to reduce unnecessary FNA procedures. In this study, we explore different architectures of one class autoencoders as a means to make this classification from a dataset of 964 Shear Wave Elastography and B-mode ultrasound images. The different autoencoders were constructed with varying numbers of layers and layer depths and were trained to encode and reconstruct images of benign nodules only. The intention is that images of benign nodules will have a lower reconstruction error than malignant nodules. This reconstruction error can then be used as the test statistic to classify images. The success of each autoencoder was evaluated using the area under a curve (AUC) and accuracy of classification.  The highest AUC achieved was 0.872, with an accuracy of 88.2% for the determination of malignancy. This study demonstrates that autoencoders offer a viable approach for thyroid nodule classification on ultrasound images.  

### Introduction
Thyroid nodules are extremely common in Adults. A very small portion of thyroid nodules are malignant. Fine Needle Aspirations biopsies are used to determine malignancy, and there is demand for a non-invasive, reliable classification method to reduce unnecessary FNAs.

### Methods

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JoeAdams4/Thyroid-Nodule-Autoencoder/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
