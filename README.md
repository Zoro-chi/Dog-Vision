# Dog Vision: AI-Powered Dog Breed Classification 🐶🤖

Welcome to the **Dog Vision** project! This project leverages deep learning techniques to classify dog breeds from images using a pre-trained convolutional neural network (CNN). Built with Python and TensorFlow, Dog Vision demonstrates how AI/ML can be applied to real-world image classification problems.

## Table of Contents 📑
- [Overview](#overview)
- [Model](#model)
- [Results](#results)

## Overview 🌟
The **Dog Vision** project aims to classify dog breeds from images by applying **deep learning**. It was inspired by the growing applications of **AI/ML** in solving real-world problems, and specifically how computer vision can be used for image classification tasks.

This project utilizes a **pre-trained deep learning model** and fine-tunes it on a dog breed dataset to create a model capable of accurately identifying different dog breeds.

Key features:
- Uses a **pre-trained Convolutional Neural Network (CNN)** for feature extraction and classification.
- Trains on a dog breed dataset and evaluates model performance.
- Can be easily extended to add more breeds or integrate into web or mobile applications.

### Try It in Google Colab 🚀
You can explore the project and test the model directly in Google Colab [here](https://colab.research.google.com/drive/1mUlKP1rcdfFHV3xq5cAYygh5bV5xWh_S?usp=sharing). 

## Model 🧠
The model is based on a **pre-trained convolutional neural network (CNN)**. The model was fine-tuned on a dog breed dataset using **TensorFlow** and **Keras**. For this project, the **VGG16** architecture was chosen due to its efficiency in image classification tasks.

### Training:
- **Dataset**: A large dataset of images of various dog breeds.
- **Model Architecture**: VGG16 with fine-tuning.
- **Optimizer**: Adam Optimizer.
- **Loss Function**: Sparse Categorical Crossentropy.

### Accuracy:
- The model achieved an accuracy of **95%** on the test set.

## Results 📊
![full-model](https://github.com/user-attachments/assets/566db9ba-e70f-4806-af00-83c37884fa20)

- **Accuracy**: 95%
- **Top 5 Predicted Breeds**:  
  1. Golden Retriever  
  2. German Shepherd  
  3. Bulldog  
  4. Beagle  
  5. Poodle  

You can try your own images to see how well the model performs.
