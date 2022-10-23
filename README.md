# Projects

### MNIST Digit Recognition Dataset

`MNIST_digit_MLP_CNN`

This notebook contains two models trained on the MNIST digit recognition dataset. First we import the data (in this case we will use a CSV file available at: https://www.kaggle.com/datasets/oddrationale/mnist-in-csv) and then we will visualize it. Next we perform some exploratory data analysis, by performing a t-Distributed Stochastic Neighbor Embedding (t-SNE) decomposition. This allows high dimensional datasets to be visualized in in a lower dimensional space. After this we need to do some data processing before we train any models. After this we will train some models, these are

- A simple 3-layer MLP neural network
- A CNN where we try to improve accuracy (this model was submitted to Kaggle https://www.kaggle.com/competitions/digit-recognizer/leaderboard#)

### Simple Moving Average Strategy

`simple_moving_averages`

This notebook shows a simple trading strategy using moving averages. This strategy is not expected to be better than a Buy and Hold strategy, but this was used as a project to revise moving averages before projects involving moving averages as features in models. Although my current research involves time series, we don’t typically consider moving averages, so I created this simple project to revised them from earlier in my education. In this project stock data is imported from Yahoo Finance and we look at Manchester United PLC (MANU) data from 2017 onwards (we will also look at Google (GOOG) too). Using this data, we take 2 moving averages on the closing price of the previous days to then build a simple strategy.

### Stock Prediction 

After revision of SMA, I am currently working on a stock prediction project and comparison of ML models for this task. 
