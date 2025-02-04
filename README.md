# PriceVision

### PriceVision is a web application designed to provide stock price predictions and help people receive all the news for buying and selling stock.

#### It's important to note that stock price prediction can be a challenging task depending on different economic factors which aren't used in this prediction program 

### Disclaimer: The predictions provided are for informational purposes only and should not be considered as financial advice. We are not responsible for any financial investment losses


## Features:
- The price prediction model uses a Long Short-Term Memory (LSTM) Recurrent Neural Network algorithm. 
- News related to a particular stock.
- User-friendly Interface 
- Graph showing historical data and prediction price 
- Buy/sell singal 


This is AAPL stock initial prediction.

<img width="500" alt="AAPL" src="https://github.com/umangptl/Software-Engineering-Project-Seminar_1/blob/main/Resources/AAPL.png">

This is AMZN stock initial prediction.

<img width="500" alt="AMZN" src="https://github.com/umangptl/Software-Engineering-Project-Seminar_1/blob/main/Resources/AmZN.png">

## Limitations of stock price prediction 
### The numbers below are based on PriceVision02 using AAPL stock from '2016-01-01' to '2023-03-01'
The prediction model for the stock closing prices has an RMSE value of 4.648 and an MAPE value of 2.435%. The RMSE represents the standard deviation of the residuals, or the differences between the predicted and actual values. A lower RMSE value indicates that the model's predictions are closer to the actual values. In this case, the RMSE value of 4.648 suggests that the model's predictions have an average error of around 4.6 points.

The MAPE, on the other hand, represents the average percentage difference between the predicted and actual values. The lower the MAPE value, the better the model's accuracy. The MAPE value of 2.435% indicates that the model's predictions have an average percentage error of around 2.4%.

Overall, the model seems to perform well in predicting the stock closing prices, with an RMSE value of 4.648 and an MAPE value of 2.435%. However, it's important to note that stock price prediction can be a challenging task depending on different economic factors which arent used in this prediction program

## Frontend using React
Machine learning predictions are made using python which then send the data react App using flask API connecting both ends 

below are some of the picture of the user interface 

<img width="500" alt="AMZN" src="https://github.com/umangptl/PriceVision/blob/main/Resources/image.png">
<img width="500" alt="AMZN" src="https://github.com/umangptl/PriceVision/blob/main/Resources/image2.png">
<img width="500" alt="AMZN" src="https://github.com/umangptl/PriceVision/blob/main/Resources/image5.jpeg">
