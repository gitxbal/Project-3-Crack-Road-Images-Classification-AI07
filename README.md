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

[1]:https://data.mendeley.com/datasets/5y9wdsg2zt/2

# Methodology

Load the dataset into Colab and extract using pyunpack package

![image](https://user-images.githubusercontent.com/110074843/184565936-17c126aa-54e4-4b49-ad01-5db200ccf1b1.png)


Split the Data

![image](https://user-images.githubusercontent.com/110074843/184566196-9f098fda-d404-49a8-8e7a-2788baf33528.png)

Use Pretrained Model MobileNetV3 as base model

![image](https://user-images.githubusercontent.com/110074843/184566981-9db3e791-c36e-4cc2-ae13-abe5789d85d4.png)

Train the model with 6 epochs

![image](https://user-images.githubusercontent.com/110074843/184568464-fc120b5c-7560-46be-b154-9e95c42064c1.png)



# Result

Achieve accuracy up to 99%

![image](https://user-images.githubusercontent.com/110074843/184567526-33f32799-7a2f-4957-a84d-bcca1402777c.png)

With validation loss

![image](https://user-images.githubusercontent.com/110074843/184567585-fe17e5a7-d5c0-4752-bbf3-145c333d176f.png)

With Validation data get confusion matrix of

![image](https://user-images.githubusercontent.com/110074843/184568493-eb33ca63-bce4-4895-a083-fda075131b4d.png)

Example of prediction

![image](https://user-images.githubusercontent.com/110074843/184568231-ad2a7c07-20d2-4785-bbfc-e705be9af509.png)

# Acknowledgement

[SHRDC][2]


[2]:https://www.shrdc.org.my/

2018 – Özgenel, Ç.F., Gönenç Sorguç, A. “Performance Comparison of Pretrained Convolutional Neural Networks on Crack Detection in Buildings”, ISARC 2018, Berlin.

Lei Zhang , Fan Yang , Yimin Daniel Zhang, and Y. J. Z., Zhang, L., Yang, F., Zhang, Y. D., & Zhu, Y. J. (2016). Road Crack Detection Using Deep Convolutional Neural Network. In 2016 IEEE International Conference on Image Processing (ICIP). http://doi.org/10.1109/ICIP.2016.7533052


