# DeepLearning_Homework

Student: Michael De Paula


<p align="center">
    <ins><b>Deep Learning:</b><br><ins>
    
</p>

In this notebook we will be building and evaluating deep learning models using FNG (Fear and Greed Models) and closing prices to determine which provides a better decision signal. 
We will be using the following imports: 

- import numpy as np
- import pandas as pd
- import hvplot.pandas
- from numpy.random import seed
- from tensorflow import random
- from sklearn.preprocessing import MinMaxScaler
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import LSTM, Dense, Dropout

We begin the code notebook for both closing prices and FNG by reading in the data csv files. We then clean up the files to begin adding train and test data. We predict the prices using a 10 day window and used 70% of the data for training. After training the data we created and tested our model FNG gave us a loss of 0.08 and closing prices gave us a loss of 0.02. 

FNG gave us the largest loss using a window of 10 days. The closing price tracks predicted  values better over time. 

