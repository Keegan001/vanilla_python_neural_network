
Multi-Layer Perceptron (MLP) for MNIST Classification in Python
This code implements a Multi-Layer Perceptron (MLP) neural network from scratch using NumPy for training on the MNIST handwritten digit classification dataset. It demonstrates the core concepts of building, training, and evaluating an MLP with:

Custom MLP class with Xavier initialization
ReLU and LogSoftmax activation functions
Negative Log-Likelihood (NLL) loss function
Gradient descent optimizer
Sequential model architecture
Features
Clear and well-structured code organization
Docstrings for improved understanding (can be further enhanced)
Comments explaining key steps
Train-test split for evaluation
Test accuracy calculation
Requirements
Python (tested with 3.x versions)
NumPy
tqdm (for progress bar visualization)
SciPy (for logsumexp)
Installation
Bash
pip install numpy tqdm scipy
Use code with caution.
content_copy
Usage
Clone or download the repository.

Run the script:

Bash
python mlp_mnist.py
Use code with caution.
content_copy
Output
The script will train the MLP model on the MNIST dataset and report the final test accuracy.
