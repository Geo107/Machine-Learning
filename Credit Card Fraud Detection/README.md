# Credit Card Fraud Detection using Self-Organizing Maps (SOM)

This repository contains code and resources for detecting credit card fraud using Self-Organizing Maps (SOM). The SOM algorithm is employed to identify patterns and anomalies in credit card transactions that may indicate fraudulent activities.

## Dataset

The dataset used for training and evaluation is the [Credit_Card_Applications.csv], which contains a large number of credit card transactions labeled as fraudulent or genuine. Ensure that the dataset is preprocessed and formatted appropriately for training the SOM model.

## Requirements

- Python 3.x
- NumPy
- Pandas
- MiniSom (Self-Organizing Maps implementation)
- Matplotlib
- Scikit-learn (for data preprocessing and evaluation)

## Usage

1. Clone this repository:

    ```
    git clone https://github.com/Geo107/Machine-Learning/Credit Card Fraud Detection.git
    ```

2. Install the required Python packages:

    ```
    pip install -r requirements.txt
    ```

3. Obtain the Credit Card Fraud Detection Dataset and preprocess it as necessary.

4. Run the Jupyter notebook `Credit Fraud Detection.ipynb` to train the SOM model and detect fraud in credit card transactions.

## Model Architecture

The Self-Organizing Map (SOM) model used for credit card fraud detection is an unsupervised learning algorithm that maps high-dimensional input data into a two-dimensional grid. Fraudulent transactions are identified as outliers in the SOM grid, separated from the regular transactions.

## Results

The trained SOM model successfully identifies fraudulent credit card transactions with a certain level of accuracy.

## Contributors

- [Geo M Benny](https://github.com/Geo107)

