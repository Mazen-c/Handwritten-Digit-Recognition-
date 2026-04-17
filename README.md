# Handwritten Digit Recognition

This project implements a Multi-Layer Perceptron (MLP) neural network for recognizing handwritten digits using the MNIST dataset. The model is built using PyTorch and trained to classify digits from 0 to 9.

## Project Structure

- `Data/`: Contains the training and testing datasets
  - `train.csv`: Training data with pixel values and labels
  - `test.csv`: Test data for predictions
- `notebook/`: Jupyter notebook containing the implementation
  - `MLP.ipynb`: Main notebook with data loading, model building, training, and prediction
  - `submission.csv`: Generated predictions for submission
- `README.md`: This file

## Requirements

- Python 3.x
- PyTorch
- Pandas
- NumPy
- Matplotlib (for visualization)


## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebook/MLP.ipynb
   ```

2. Run the cells in order to:
   - Load and preprocess the data
   - Build and train the MLP model
   - Make predictions on test data
   - Generate submission file

## Model Architecture

The MLP consists of:
- Input layer: 784 neurons (28x28 pixel images flattened)
- Hidden layer 1: 128 neurons with ReLU activation
- Hidden layer 2: 64 neurons with ReLU activation
- Output layer: 10 neurons (one for each digit 0-9)

## Training

- Loss function: Cross-Entropy Loss
- Optimizer: Adam with learning rate 0.001
- Epochs: 10

## Contributing

Feel free to fork the repository and submit pull requests for improvements.
