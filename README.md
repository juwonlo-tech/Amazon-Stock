# Amazon-Stock-RNN
## Amazon stock price time series forcasting

Given the uncertainty surrounding stock prices and with the amazing progress in machine learning, 
I developed a neural network to predict stock prices.

### The data
The stock price data used is Amazon's historical data from 2012 to 2022. 
It was downloaded from https://www.nasdaq.com/market-activity/stocks/amzn/historical

### Data Preview
<img width="730" alt="Screenshot 2022-11-03 at 2 30 39 PM" src="https://user-images.githubusercontent.com/77176412/199816651-c42d9f19-3754-4422-9fd8-e1ff4c63d620.png">

### Data Visualization
The values of the closing stock price was plotted against the dates

<img width="730" alt="Screenshot 2022-11-03 at 2 34 05 PM" src="https://user-images.githubusercontent.com/77176412/199817288-3f4057ea-2dac-4686-ae69-0a6f3ecca0d8.png">

### Model Development
A hybrid model of stacked SimpleRNNs and Conv1D. The model was trained on a mutated SGD optimizer (adam) and 5 epochs.

The final result shows that the model did a great job predicting the daily Amazon closing stock price.

<img width="730" alt="Screenshot 2022-11-03 at 2 45 17 PM" src="https://user-images.githubusercontent.com/77176412/199819334-4edff08d-6e7b-4fb3-8632-f85f45bb6a0a.png">
