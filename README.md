# WiDS-2023

This repository contains my contribution to the 2023 Women in Data Science dackathon.
The data set is available on Kaggle(https://www.kaggle.com/competitions/widsdatathon2023/data). The dataset contained 3 files; train, test and sample solutions datasets

I started by importing the necessary libraries into my notebook then reading data into my notebook using the pandas library.
This was then followed by data exploration using the inbuilt pandas functions such as head, tail, info, describe and isna.
I used the autoviz library to get suggestions on the various places to clean my data since the dataset was large and had many features.
You can install the autoviz library as follows : pip install autoviz
I cleaned my data by defining a function to fill in the missing values and detect and drop any outliers. I changed the start_date column to datetime so that I can be able to apply time series.
I then selected the best features to use for modelling using GridSearchCV and then proceeded to creating a linear regression model
