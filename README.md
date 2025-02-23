# Brain MRI Scan Classification
This Jupyter notebook is designed to classify brain MRI images into four categories: glioma, meningioma, no tumor, and pituitary tumor. The notebook uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to perform the classification task.

## Introduction
The goal of this project is to classify brain MRI images into four categories using a deep learning model. The dataset used in this notebook is the Brain Tumor MRI Dataset from Kaggle, which contains images of brain scans labeled with the corresponding tumor type or no tumor.

## Setup and Dependencies
The notebook requires several Python libraries, including TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, and OpenCV. These libraries are used for data manipulation, visualization, and building the neural network model. Python version is 3.11.9. Requires the instalation of Tensorflow, opencv-python, and kagglehub.

![image](https://github.com/user-attachments/assets/b58e7b87-b5b0-4ce2-a781-6e95c340fe60)

## Data Loading and Preprocessing
The dataset is loaded using the Kaggle API. The images are resized to 224x224 pixels and normalized. The labels are converted to categorical format for the model.

![image](https://github.com/user-attachments/assets/07289237-3d52-4b63-93c3-324a218ac593)
![image](https://github.com/user-attachments/assets/48eb2468-2a8e-45bb-9383-da273b5fa283)
![image](https://github.com/user-attachments/assets/5d0d3c3c-c1d6-4217-a150-371ea0f900d6)

## Model Architecture
The CNN model consists of four convolutional layers followed by max-pooling layers, a flattening layer, and fully connected layers with dropout for regularization.

![image](https://github.com/user-attachments/assets/415be44a-c537-4757-9695-902b104d5612)
![image](https://github.com/user-attachments/assets/482e816a-8fbb-4dc9-934e-754e9a1632ee)

## Model Training
The model is compiled with the Adamax optimizer and trained using the training data. Data augmentation and early stopping is applied to improve generalization and prevent overfitting.

![image](https://github.com/user-attachments/assets/68c6bbf6-b129-417a-9397-440d922fe795)


## Evaluation
The model's performance is evaluated on the test set, and the accuracy is reported. The model achieves an accuracy of 90 - 92% and is generalized.

![image](https://github.com/user-attachments/assets/d0842eaf-84d9-4aba-a019-375baa34b15d)
![image](https://github.com/user-attachments/assets/824e7a8f-d07c-42b3-be81-ecb2c2169caa)
![image](https://github.com/user-attachments/assets/7872c75c-5ab1-48f3-af8b-32dcd7c9eec0)
![image](https://github.com/user-attachments/assets/c3de3e48-2a31-43eb-9b22-0cfa6631cd8e)
![image](https://github.com/user-attachments/assets/11ca05db-3502-4eeb-804f-2bd97917dd66)

## Conclusion
This notebook demonstrates the process of classifying brain MRI images using a CNN. The model achieves a high accuracy on the test set, indicating its effectiveness in distinguishing between different types of brain tumors and no tumor cases. My goal is to achieve a 

For further improvements, consider experimenting with different model architectures, hyperparameters tuning, implementing transfer learning and reinforcement learning, and data augmentation techniques.
