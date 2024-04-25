# Google Stock Price Prediction using Recurrent Neural Network (RNN)

This repository contains code and resources for predicting Google stock prices using a Recurrent Neural Network (RNN). The model aims to forecast the future stock prices of Google based on historical stock price data and possibly other relevant features.

## Dataset

The dataset used for training and evaluation is the historical stock price data of Google, which can be obtained from various sources such as Yahoo Finance or Alpha Vantage. Ensure that the dataset is preprocessed and formatted appropriately for training the RNN model. Here dataset used here is of year 2017.

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
    git clone https://github.com/your-username/google-stock-prediction-rnn.git
    ```

2. Install the required Python packages:

    ```
    pip install -r requirements.txt
    ```

3. Obtain the historical stock price data of Google and preprocess it as necessary. Place the dataset in the directory.

4. Run the Jupyter notebook `Stock_Prediction.ipynb` to train the RNN model and make predictions.

## Model Architecture

The Recurrent Neural Network (RNN) model used for predicting Google stock prices consists of one or more recurrent layers such as LSTM (Long Short-Term Memory) or GRU (Gated Recurrent Unit). The input to the model is historical stock price data, and the output is the predicted future stock prices(of 2017).

## Results

The trained RNN model achieves a certain level of accuracy in predicting Google stock prices.


## Contributors

- [Geo M Benny](https://github.com/Geo107)
