# Brain_MRI
This Jupyter notebook is designed to classify brain MRI images into four categories: glioma, meningioma, no tumor, and pituitary tumor. The notebook uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to perform the classification task.

## Table of COntents
-[Introduction](#introduction)
-[Setup and Dependencies](#set_and_dependencies)
-[Data Loading and Preprocessing](#data_loading_and_preprocessing)
-[Model Architecture](#model_architecture)
-[Model Training](#model_training)
-[Evaluation]
-[Conclusion]

## Introduction
The goal of this project is to classify brain MRI images into four categories using a deep learning model. The dataset used in this notebook is the Brain Tumor MRI Dataset from Kaggle, which contains images of brain scans labeled with the corresponding tumor type or no tumor.

## Setup and Dependencies
The notebook requires several Python libraries, including TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, and OpenCV. These libraries are used for data manipulation, visualization, and building the neural network model.

![image](https://github.com/user-attachments/assets/d97682c0-4e9a-4f5d-bd21-4c0863c2ccc2)

## Data Loading and Preprocessing
The dataset is loaded using the Kaggle API. The images are resized to 224x224 pixels and normalized. The labels are converted to categorical format for the model.
![image](https://github.com/user-attachments/assets/07289237-3d52-4b63-93c3-324a218ac593)
![image](https://github.com/user-attachments/assets/48eb2468-2a8e-45bb-9383-da273b5fa283)
![image](https://github.com/user-attachments/assets/5d0d3c3c-c1d6-4217-a150-371ea0f900d6)

