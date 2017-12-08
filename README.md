# Stock-Market-Prediction

Forecasting of stock market is a way to predict future prices of stocks. The Stock prices are dynamic day by day, so it is hard to decide what is the best time to buy and sell stocks. It is a long time attractive topic for researcher and investors from its existence. Machine Learning provides a wide range of algorithms, which has been reported to be quite effective in predicting the future stock prices. In this project, we explored different data mining algorithms to forecast stock market prices for NSE stock market. Our goal is to compare various algorithms and evaluate models by comparing prediction accuracy. We examined a few models including Linear regression, Arima, LSTM, Random Forest and Support Vector Regression. Based on the accuracy calculated using RMSE of all the models, we predicted prices of different industries. For forecasting, we used historical data of NSE stock market and applied a few preprocessing methods to make prediction more accurate and relevant.

## Dataset

Dataset was taken from [here](https://www.kaggle.com/ramamet4/nse-company-stocks) and includes India stocks and our index covers a diverse set of sectors featuring many indian companies.

## Getting started

1. Clone the project.
2. Download the [dataset](https://github.com/ambikabohra/Stock-Market-Prediction/blob/master/groupeddf.csv.zip) and preprocessed dataset from [here](https://github.com/ambikabohra/Stock-Market-Prediction/blob/master/groupeddf.csv.zip).
3. Install Jupyter Notebook.
4. Install required libraries:
```bash
$ pip install numpy
```
```bash
$ pip install pandas
```
```bash
$ pip install scipy
```
```bash
$ pip install keras
```
```bash
$ pip install matplotlib
```
```bash
$ pip install seaborn
```
## Workflow and System Architecture

![workflow](https://github.com/ambikabohra/Stock-Market-Prediction/blob/master/Images/workflow1.png)

## Prediction 

Following algorithms are used for time series analysis:

1. Linear regression
2. Support Vector Regression (SVR)
3. Long Short Term Memory (LSTM)
4. Autoregressive Integrated Moving Average (ARIMA)
5. Random Forest

## Comparision of the models used 

For 1 company (3IINFOTECH)

![comparision](https://github.com/ambikabohra/Stock-Market-Prediction/blob/master/Images/graphs.png)

### Conclusion

1. Algorithms compared using RMSE calculated for each model.  
2. LSTM and Arima model gave lowest RMSE and highest accurate prediction. So these are winning algorithms.
3. SVR gave highest RMSE.
