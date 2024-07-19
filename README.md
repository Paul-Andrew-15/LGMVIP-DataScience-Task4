# LGMVIP-DataScience-Task4
## Handwritten Digit Classification with CNN and TensorFlow
This project aims to develop a neural network capable of classifying handwritten digits using the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits ranging from 0 to 9.

## Key Steps:
1. Data Loading and Preprocessing:
Load the MNIST dataset.
Normalize the pixel values to the range [0, 1].
Reshape the data to include a single grayscale channel.

2. Model Building:
Construct a Convolutional Neural Network (CNN) using TensorFlow's Keras API.
The model includes convolutional layers for feature extraction, max-pooling layers for down-sampling, and dense layers for classification.

3. Model Compilation:
Compile the model using the Adam optimizer and sparse categorical cross-entropy loss function.
Track accuracy as the performance metric.

4. Model Training:
Train the model on the training dataset for a specified number of epochs.
Validate the model using the test dataset.

5. Model Evaluation:
Evaluate the trained model's performance on the test dataset to determine its accuracy.

6. Results Visualization:
Plot training and validation accuracy to visualize the model's performance over epochs.

7. Prediction:
Use the trained model to make predictions on new handwritten digit images.

This project provides a foundational understanding of building and training CNNs for image classification tasks, making it ideal for beginners in machine learning and deep learning.
