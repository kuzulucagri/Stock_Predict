# Stock_Predict

#### In that project I worked on facebook's price dataset.
#### First of all, I used libraries which are numpy, matplotlib, pandas, pandas_datareader, datetime, scikit-learn and tensorflow.
#### Then I defined datetime 2013-1-1 to 2021-1-1. After that load the data by pandas_datareader library.
#### I had numerical numbers and I need to scale that so I used MinMaxScaler.
#### After this step, I define x_train and y_train in addition used for loops.
#### Now I need to build my model so I built it with LSTM and compiled it with adam optimizer.
#### I loaded my test data and predicted it then transform my datas.
#### I used matplotlib library for visualization
![Ekran Alıntısı](https://user-images.githubusercontent.com/70862062/114314235-8cd5e500-9b02-11eb-84f7-e0b357358954.PNG)

#### In conclusion, I wanted to predict next day so I used model.predict and my tomorrow's prediction is 263.7373
