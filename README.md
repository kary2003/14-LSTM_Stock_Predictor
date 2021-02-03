# LSTM Stock Predictor

![image](https://user-images.githubusercontent.com/70820754/106659604-35445780-655c-11eb-901d-a0eae9517092.png)

## LSTM units in RNN(Recurrent Neural Network) Models. 

The data for this project will allow us to create RNN models to predict closing prices. One of the notebooks will use the fear and greed values to predict the closing prices and the second notebook will use the historical data to predict the next day's closing price. 

For both notebooks I will utilize this function:

![1](https://user-images.githubusercontent.com/70820754/106677450-fde2a480-6575-11eb-9644-b65f8612db96.png)
    
provided in the starter file.  

Each model will use 70% of the data for training and 30% for testing. 

Data will be scaled using MinMaxScaler to scale the x & y values for the model. 

---

#### Data

[btc_historic.csv](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Starter%20Files/btc_historic.csv)

[btc_sentiment.csv](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Starter%20Files/btc_sentiment.csv)

### Files

[Closing Prices Starter Notebook](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Starter%20Files/lstm_stock_predictor_closing.ipynb)

[FNG Starter Notebook](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Starter%20Files/lstm_stock_predictor_fng.ipynb)

- - -

## Conclusion: Performance Model Evaluation

### Which model has a lower loss?
The closing price model has a lower loss. 

### Which model tracks the actual values better over time?
The Closing price model. 

### Which window size works best for the model?
The best performing window size is 1.

### Images
#### Closing Price comparison 1 day & 10 days at 10 epochs:
![image](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Images/1-1day.png)
#### Closing Price comparison 1 day & 10 days at 20 epochs:
![image](https://github.com/kary2003/14-LSTM_Stock_Predictor/blob/main/Images/4-10%20day.png)

### Resources

[Keras Sequential Model Guide](https://keras.io/getting-started/sequential-model-guide/)

[Illustrated Guide to LSTMs](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)

[Stanford's RNN Cheatsheet](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)

- - -
