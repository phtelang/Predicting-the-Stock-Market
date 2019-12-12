## Predicting the Stock Market
In this project, I worked with data from the __[S&P500 Index.](https://en.wikipedia.org/wiki/S%26P_500_Index)__ The S&P500 is a stock market index. Indexes aggregate the prices of multiple stocks together, and allow you to see how the market as a whole is performing. We will be using historical data on the price of the S&P500 Index to make predictions about future prices. Predicting whether an index will go up or down will help us forecast how the stock market as a whole will perform. Since stocks tend to correlate with how well the economy as a whole is performing, it can also help us make economic forecasts.

Each row in the file contains a daily record of the price of the S&P500 Index from 1950 to 2015. We will use this dataset to develop a predictive model. We will train the model with data from 1950-2012, and try to make predictions from 2013-2015.

### Summary of Results
The Mean Absolute Error is off by just over 16 points and our average closing price is just under 1875. This isn't a model we would want to use to actually make stock trades, but it isn't bad considering we only used features derived from the closing price and volume history.

To view the code and graphs accurately, please click on this link as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the source csv file on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
