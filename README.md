# Number-Recognizing-Neural-Network

This Repository documents and stores my first attempt at making a neural network from scratch. The aim of this is to be able to recogize numbers 0-9 from photos.

## Overview

This project implements a fully connected neural network without relying on machine learning frameworks.

The network takes a 28×28 image and predicts the number it represents.

Link to my whiteboard: https://drive.google.com/file/d/12YPSdP3LQT5bK8W6g_KcyWpt9CTSGPSM/view?usp=sharing

## Architecture

- **Input layer:** 784 neurons (28×28 pixels)
- **Hidden layer:** 128 neurons with ReLU
- **Output layer:** 10 neurons with Softmax

## Implementation

Implemented manually using NumPy:

- Weight and bias initialization
- Forward Propagation
- ReLU and Softmax activation functions
- One-hot encoding
- Backward Propagation
- Gradient descent
- Prediction and accuracy evaluation

## Results

| Metric | Result |
|---|---:|
| Training accuracy | 94.08% |
| Validation accuracy | 92.90% |
| Learning rate | 0.1 |
| Training iterations | 1,000 |

## Requirements

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

Trained on this dataset.

[Dataset source](https://www.kaggle.com/datasets/ompanpatil12/simple-mnist-nn-from-scratch-numpy-no-tfkeras)

## Running the Project

1. Clone this repository.
2. Install the required dependencies.
3. Open the .ipynb file in Jupyter Notebook.
4. Run the cells in order.

## What I Learned

This project was a great starting point in my journey in machine learning. Because of this I now have an understanding of how models actually function on their base level. Thanks to Samson Zhang for inspiration, I made a few tweaks to his code but most of it is very similar.

Link to his original video: https://www.youtube.com/watch?v=w8yWXqWQYmU&t=745s
