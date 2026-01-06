# Fashion-MNIST Deep Learning Analysis

This project explores the implementation and optimization of Feedforward Neural Networks (FNN) using the Fashion-MNIST dataset. It focuses on hyperparameter tuning, regularization techniques, and comparing different optimization algorithms.

## Project Overview

The goal is to build a flexible neural network architecture and systematically improve its performance through experimentation.

**Key tasks implemented:**
* **Data Visualization:** Visualizing sample images from each of the 10 fashion classes.
* **Model Implementation:** Building a Feedforward Neural Network using TensorFlow/Keras with adjustable depth and width.
* **Grid Search:** Custom implementation to tune hyperparameters including:
    * Number of hidden layers & neurons
    * Optimizers (SGD, Adam, RMSprop, etc.)
    * Learning rates & Weight decay
    * Batch sizes & Epochs
* **Regularization:** Investigating the impact of Dropout and Batch Normalization.

## Dependencies

* Python 3.x
* TensorFlow / Keras
* PyTorch / Torchvision (used for dataset loading)
* Scikit-learn
* Matplotlib
* Pandas

## How to Run

1. Clone the repository.
2. Install the dependencies.
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Deep Learning Optimization on Fashion-MNIST.ipynb"
