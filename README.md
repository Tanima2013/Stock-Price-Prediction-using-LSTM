# Stock-Price-Prediction-using-LSTM
Stock Price Prediction
<br>
Author - Tanima Khair
This project aims to predict stock prices using a dataset from Microsoft (MSFT). Initially, the data is processed and transformed, focusing on the 'Date' and 'Close' price columns. Time series windowing techniques are applied to prepare the data for training a Long Short-Term Memory (LSTM) neural network model. The dataset is split into training, validation, and testing sets. The LSTM model architecture includes input layers, LSTM layers, and dense layers, followed by compilation with Mean Squared Error (MSE) loss and Adam optimizer. After training the model for 100 epochs, predictions are made on the training, validation, and testing sets, visualized alongside the actual stock prices. The model's performance on each set is evaluated, demonstrating its ability to capture the trends and fluctuations in Microsoft's stock prices over time.
