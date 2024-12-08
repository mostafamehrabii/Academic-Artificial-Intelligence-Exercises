# MNIST Classification with Naive Bayes, CNN, and MLP

This repository contains implementations for classifying MNIST and FashionMNIST datasets using different machine learning models. The project is structured into several sections:

## **1. MNIST Classification with Gaussian Naive Bayes**
In this section, a **Gaussian Naive Bayes** classifier is applied to the MNIST dataset. The implementation begins by loading and splitting the MNIST dataset into training and testing sets. The classifier is trained on the raw pixel values and evaluated based on its accuracy. The section also visualizes the confusion matrix of predictions.

Key points:
- **Model**: Gaussian Naive Bayes
- **Dataset**: MNIST
- **Features**: Raw pixel values
- **Visualization**: Confusion matrix

## **2. MNIST Classification with Feature Extraction (Row/Column Averages)**
This section explores an alternative approach to feature extraction by using **row and column averages** of MNIST images as features. After calculating the averages, the data is split, and a **Gaussian Naive Bayes** model is trained and evaluated. The accuracy is compared with the previous section's approach.

Key points:
- **Feature Extraction**: Row and column averages of images
- **Model**: Gaussian Naive Bayes
- **Dataset**: MNIST
- **Visualization**: Confusion matrix comparison between two approaches

## **3. MNIST Classification with Convolutional Neural Network (CNN)**
In this section, a more advanced model, a **Convolutional Neural Network (CNN)**, is implemented using TensorFlow and Keras. The CNN model is designed with two convolutional layers followed by max pooling layers, and it is trained to classify MNIST digits. The model's accuracy is evaluated after training.

Key points:
- **Model**: Convolutional Neural Network (CNN)
- **Dataset**: MNIST
- **Features**: Image pixel values
- **Evaluation**: Accuracy on test data

## **4. FashionMNIST Classification with Multi-Layer Perceptron (MLP)**
In this section, the **FashionMNIST** dataset is used, and an **MLP** (Multi-Layer Perceptron) model is trained to classify images. The dataset is preprocessed with normalization, and the model is trained using PyTorch. The section also evaluates the accuracy of the model on a validation set.

Key points:
- **Model**: Multi-Layer Perceptron (MLP)
- **Dataset**: FashionMNIST
- **Framework**: PyTorch

## **5. FashionMNIST with Weight Pruning**
The final section demonstrates **weight pruning** on the MLP model for **FashionMNIST**. The weights of the model are pruned based on the similarity between them, and different pruning percentages are tested to observe the impact on accuracy.

Key points:
- **Model**: Multi-Layer Perceptron (MLP) with weight pruning
- **Dataset**: FashionMNIST
- **Evaluation**: Accuracy vs. pruning percentage
