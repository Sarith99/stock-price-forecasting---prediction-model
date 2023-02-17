# stock-price-forecasting---prediction-model
Machine Learning model for stock price forecasting and prediction using LSTM. Stock prices from 1986 to 2023 were used inside the model as dataset.

Link for the Dataset: https://finance.yahoo.com/quote/MSFT/history/

The dataset was consisted with 9306 rows and 7 columns.

Before model creation, Converted the dataset into type that can be used for supervised learning. 

The neural network is consists with LSTM layer and 3 Dense layers. Relu is the activation function that used in those dense layers.Mean Square Error was used as the lose function, Adam was used as the optimizer and set learning rate into 0.001, the mean_absolute_error used as the metrics. The model was trained by using 100 epochs.


Becuase of the accuracy issues, dismiss the dataset rows into 476 by changing the period for 1 year(latest).

All aspects are included inside the model.
