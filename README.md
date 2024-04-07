# Stock Prediction Project

This project aims to predict stock prices using various machine learning models such as Random Forest (RF), Long Short-Term Memory (LSTM), and Recurrent Neural Network (RNN). The prediction is based on historical stock data obtained from pre-downloaded CSV files. The project was developed in Google Colab and utilizes Jupyter Notebook (ipynb) format.

## Data Sources

The project uses historical stock data of the following companies:
- GDX
- TWTR
- USAK
- UVSP

The data is pre-downloaded and stored in CSV files, which are accessed in the notebook through Google Drive. You can download the CSV file from the following link:
[Download CSV File](https://drive.google.com/file/d/1XEOgoRgCB1yJwfkDzlwHyHcbczJf2dNi/view?usp=drive_link)

## Machine Learning Models

### Random Forest (RF)

Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees at training time and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees. In this project, the RF model is utilized for stock price prediction.

### Long Short-Term Memory (LSTM)

LSTM is a type of recurrent neural network (RNN) architecture used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It can process not only single data points but also entire sequences of data, such as time-series data used in this project for stock prediction.

### Recurrent Neural Network (RNN)

RNN is another type of neural network architecture suitable for sequence modeling. It processes sequences of data by maintaining internal memory. In this project, RNNs are employed alongside LSTM for stock price prediction.

## Usage

To run the project, follow these steps:
1. Upload the provided CSV files containing historical stock data to your Google Drive.
2. Open the Jupyter Notebook (ipynb) file in Google Colab.
3. Mount your Google Drive in the notebook to access the CSV files.
4. Execute the cells in the notebook to train and evaluate the machine learning models.
