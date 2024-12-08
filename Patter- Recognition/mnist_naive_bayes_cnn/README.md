# MNIST Classification with Naive Bayes and Neural Networks

This project demonstrates the implementation of various classification models using the MNIST dataset. The models range from Naive Bayes classifiers to Convolutional Neural Networks (CNNs) for performance comparison and enhancement.

## Dataset

The MNIST dataset is used for all implementations. It contains images of handwritten digits (0–9) with corresponding labels.

## Implementations

### Section 1: Gaussian Naive Bayes on Raw Pixels
- **Features:** Raw pixel values.
- **Classifier:** Gaussian Naive Bayes.
- **Performance Metric:** Accuracy and confusion matrix visualization.

### Section 2: Gaussian Naive Bayes on Derived Features
- **Features:** Row and column averages of image pixels.
- **Classifier:** Gaussian Naive Bayes.
- **Performance Metric:** Accuracy and confusion matrix visualization.

### Section 3: Convolutional Neural Networks (CNN)
- **Features:** Pixel values normalized to [0, 1].
- **Model:** CNN with 2 convolutional layers, followed by dense layers.
- **Performance Metric:** Test accuracy.

### Revision Section: Multinomial Naive Bayes
- **Features:** Binarized pixel values.
- **Classifier:** Multinomial Naive Bayes.
- **Performance Metric:** Accuracy.

### Convolution Method with Average Pooling
- **Features:** Average pooling over 3x3 windows.
- **Model:** CNN with average pooling layer.
- **Performance Metric:** Test accuracy.
