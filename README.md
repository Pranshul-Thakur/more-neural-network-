# Handwritten Digit Classifier

A neural network implementation from scratch using NumPy for recognizing handwritten digits from the MNIST dataset.

## Features

- Two-layer neural network
- ReLU activation for hidden layer
- Softmax activation for output layer
- Gradient descent optimization
- Training visualization and accuracy tracking

## Installation

```bash
pip install numpy pandas matplotlib
```

## Dataset

Place the MNIST `train.csv` file in the project directory. The dataset should contain 785 columns (1 label + 784 pixel values).

## Usage

```bash
python main.py
```

The script will:
1. Load and preprocess the dataset
2. Train the neural network for 500 iterations
3. Display predictions on test images
4. Calculate final accuracy on validation set

## Network Architecture

- Input: 784 neurons (28x28 pixel images)
- Hidden layer: 10 neurons with ReLU activation
- Output layer: 10 neurons with Softmax activation

## Training Parameters

- Learning rate: 0.10
- Iterations: 500
- Train/validation split: 41000/1000
