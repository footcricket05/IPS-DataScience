# Breast-cancer-classification


## Overview
This project focuses on using Convolutional Neural Networks (CNN) and Transfer Learning to classify breast cancer tumors as benign or malignant. The dataset used for this project is the Breast Cancer Histopathological Database (BreakHis), which can be downloaded from here.

## Objective
The objective of this project is to develop a model that can accurately classify breast cancer tumors as benign or malignant using histopathological images of breast tissue.

## Dataset
The BreakHis dataset consists of 7,909 microscopic histopathology images of breast cancer tumors, which are classified into benign and malignant classes. The dataset is divided into training and validation sets, with 70% of the data used for training and 30% for validation. The training set consists of 5,537 images, and the validation set consists of 2,372 images.

Link- https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/

## Approach
The approach taken in this project is to use transfer learning with a pre-trained CNN model, specifically the VGG-16 model. The VGG-16 model is fine-tuned on the BreakHis dataset, and the fully connected layers are replaced with a new classifier layer. The model is then trained using the training data and evaluated using the validation data.

## Results
The model achieved an accuracy of 89.38% on the validation set, indicating that it can accurately classify breast cancer tumors as benign or malignant based on histopathological images.

## Conclusion
In conclusion, this project demonstrates the effectiveness of using transfer learning with pre-trained CNN models for breast cancer classification. The model achieved a high level of accuracy on the validation set, indicating that it can be a valuable tool for assisting medical professionals in the diagnosis of breast cancer. However, it should be noted that this model should not be used as a substitute for medical professionals, and any diagnosis should always be confirmed by a trained medical professional.

