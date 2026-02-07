# ML Assignment - Supervised Regression

## Problem Statement
The objective of this assignment is to train a Convolutional Neural Network (CNN)
to predict the (x, y) coordinates of a bright pixel from grayscale images.

## Dataset
A synthetic dataset was generated where each 50×50 image contains exactly one
bright pixel. The pixel position represents the ground-truth coordinate.

## Model
A CNN-based regression model was implemented using TensorFlow/Keras.
The network learns spatial relationships between pixel location and coordinate output.

## Training
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam
- Train/Validation split used

## Results
The model successfully predicts pixel coordinates with low error.
Training and validation loss curves show stable convergence.
Prediction plots compare ground-truth and predicted coordinates.

## Dependencies
- Python 3.10+
- NumPy
- Matplotlib
- TensorFlow
- scikit-learn

## How to Run
Open `ML_Assignement.ipynb` in Google Colab or Jupyter Notebook and run all cells.
