# Bank Churn Modeling using Simple Artificial Neural Network (ANN)

This repository contains code and resources for building a simple artificial neural network (ANN) model to predict bank churn. The model aims to predict whether a bank customer will churn (leave the bank) based on various features such as customer demographics, banking activity, and transaction history.

## Dataset

The dataset used for training and evaluation is the [Churn_Modelling.csv], which contains information about bank customers including their age, gender, credit score, balance, etc., along with a binary label indicating whether they churned or not.

## Requirements

- Python 3.x
- NumPy
- Pandas
- TensorFlow
- Scikit-learn
- Matplotlib

## Usage

1. Clone this repository:

    ```
    git clone https://github.com/Geo107/Machine-Learning/tree/main/Bank Churn Modelling.git
    ```

2. Install the required Python packages:

    ```
    pip install -r requirements.txt
    ```

3. Download the dataset  and place it in the  directory.

4. Run the Jupyter notebook `Bank_Churn_Model.ipynb` to train the ANN model and evaluate its performance.

## Model Architecture

The simple artificial neural network (ANN) model consists of an input layer, one or more hidden layers, and an output layer. The input layer takes the features of bank customers as input, the hidden layers perform various transformations, and the output layer produces the probability of churn.

## Results

The trained ANN model achieves an accuracy of 90% on the test set, with a precision of 87% and a recall of 93%.
