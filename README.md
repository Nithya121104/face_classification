This repository contains an image classification model designed to detect emotions such as happy, sad, and angry from images. The model uses deep learning techniques, specifically Convolutional Neural Networks (CNNs), and leverages a pre-trained model like ResNet50 for feature extraction. This model is capable of detecting multiple emotions simultaneously, treating this as a multi-label classification problem.

Key Features
Multi-label classification: The model can classify multiple emotions in an image (e.g., an image can be both "happy" and "angry").

Pre-trained model: Utilizes the ResNet50 model for efficient transfer learning, reducing the training time and improving accuracy.

Image Augmentation: Implements data augmentation techniques to improve model generalization.

Flexible Output: The model outputs a probability for each emotion (happy, sad, angry), allowing thresholding for emotion detection.
