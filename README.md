# MNIST Digit Classifier (Custom CNN in NumPy)

## Overview
Implementation of a Convolutional Neural Network from scratch using NumPy for handwritten digit classification on MNIST.

This project focuses on understanding the internal mechanics of CNNs by manually implementing:
- convolution
- activation functions
- pooling
- backpropagation
- training loop

## Key Features
- No deep learning frameworks used for model building
- Manual forward + backward propagation
- Loss tracking and visualization
- Prediction visualization on test samples

## Tech Stack
- Python
- NumPy
- Matplotlib
- TensorFlow (dataset loading only)

## Results
- Training accuracy: ~30–40%
- Test accuracy: ~20–30%
- Loss decreases across epochs

## Notes
- Convolution backpropagation is simplified
- Dataset size reduced for faster training

## Sample Outputs

### Loss Curve
![Loss]()

### Predictions
![Predictions](predictions.png)

## How to Run
Run the notebook in Google Colab or locally after installing:
pip install numpy matplotlib tensorflow scikit-learn
