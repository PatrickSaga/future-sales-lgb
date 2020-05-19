# Future-prices-lgb
Ipython Notebook for the Kaggle competition [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales).
The aim of this repository is to provide a machine learning workflow for time series data, generating an enriched data input including lags in order to predict future prices with an LGB regressor algorithm.

The current version of the code achieves a public score of 0.91793 based on [RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation) metric for the Predict Future Sales competition, leading to a Top 27% result in the leaderboard. True target values are clipped into [0,20] range.

## Kaggle competition description
From the competition [homepage](https://www.kaggle.com/c/competitive-data-science-predict-future-sales):
> In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - [1C Company](https://1c.ru/eng/title.htm). 
> We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.

## Table of contents
1. Load data
2. Data exploration (EDA)
3. Missings cleaning
4. Feature engineering
5. Mean encoding and generation of lag
6. Data preparation and prediction (LGBoost) 

### Dependencies
- [IPython](http://ipython.org/)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [SciKit-Learn](https://scikit-learn.org/stable/)
- [SciPy](https://www.scipy.org/)
- [Seaborn](https://seaborn.pydata.org/#)
- [Matplotlib](https://matplotlib.org/)
- [XGBoost](https://xgboost.readthedocs.io/en/latest/#)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/#)


## Contributors
Patrick Sánchez Galea ([Kaggle profile](https://www.kaggle.com/saga21))
