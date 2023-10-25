# PyTorch - Customers exiting a bank analysis
## Overview
This repository contains an implementation of an Artificial Neural Network (ANN) built using PyTorch to predict bank customer churn based on a dataset with 10,000 records. By understanding which customers are more likely to leave, banks can proactively address their concerns, thereby improving customer retention.

## Key Features
Dataset: Contains 10,000 records of bank customers along with their attributes and whether they left the bank.
ANN Architecture: Designed with 10 input nodes, 3 hidden layers, and 1 output node. 
Training: The model is trained using 'Adam Optimizer' and a 'Binary Cross-Entropy' to ensure optimal parameter adjustments.
Evaluation: Implemented binary accuracy metric to evaluate the model's performance on test data. 
Visualization: Incorporated loss and accuracy plots over epochs to understand model convergence.
Regularization: Implemented Dropout method to eliminate overfitting.

## How to Use:
1. Clone this repository.
1. Open main_nn.ipynb file.
1. Look at the dropout comparison before running any code!
1. Install the required packages listed in requirements.txt.
1. Open data_preprocess.ipynb file and run all the cells
1. Again open and run the main_nn.ipynb file to train and evaluate the neural network.
1. Adjust hyperparameters in the Hyperparameter section, if necessary.








