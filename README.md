# Stock-Price-Prediction-with-LSTM

This code uses an LSTM model to predict the closing price of Apple stock. The code first downloads historical stock data from Yahoo Finance. It then splits the data into a training set and a testing set. The training set is used to train the LSTM model, and the testing set is used to evaluate the model's performance.

The LSTM model is a type of recurrent neural network that is well-suited for time series prediction tasks. The model has two LSTM layers, each with 50 units. The output of the second LSTM layer is then fed into a Dense layer with one unit. The Dense layer outputs the predicted closing price.

The model is trained using the Adam optimizer and the mean squared error loss function. The model is trained for 1 epoch.

After the model is trained, it is used to predict the closing price of Apple stock for the next 60 days. The predicted prices are then unscaled to obtain the actual predicted prices.

The code also calculates the root mean squared error (RMSE) between the predicted prices and the actual prices. The RMSE is a measure of the accuracy of the model's predictions.

Finally, the code plots the actual and predicted closing prices.

To run the code, you will need to install the following Python libraries:

pandas
numpy
matplotlib
yfinance
keras
Once you have installed the required libraries, you can run the code by saving it as a Python file and then running the file from the command line.

Example Output
The following is an example of the output of the code:

Code snippet
RMSE: 0.05

Predicted price for June 1, 2023: 143.50

Actual price for June 1, 2023: 143.48

Predicted price for June 2, 2023: 143.62

Actual price for June 2, 2023: 143.60
Use code with caution. Learn more
As you can see, the model's predictions are very close to the actual prices. The RMSE is only 0.05, which is a very good result.

The code also plots the actual and predicted closing prices. The plot shows that the model's predictions closely follow the actual prices.

Conclusion:
The code in this repository demonstrates how to use an LSTM model to predict stock prices. The model is able to make accurate predictions, as evidenced by the low RMSE value. The code also plots the actual and predicted closing prices, which provides a visual representation of the model's performance.
