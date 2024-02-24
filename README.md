# Concrete-Strength-Analysis

## Data
source : https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

## Purpose
To predict the Compressive Strength based on input variables without using Neural Networks.

## Process

I started with EDA exploring the variables and their relationships. There was a lot of non linear relationships in the data.
At first, I just focused on the raw data and relative magnitude of the features (Kg in m^3 mixture), but perhaps a percentage of total mixture is worth exploring and perhaps more indicative of strength than a scalar value.

I wanted to focus on "less" complex models than neural networks as I am still learning and want to get the basics down. I focused on ensemble methods starting with RandomForestRegressor, but will expand to XGBoost and AdaBoost down the road. Eventually, I would like to explore neural networks to answer how to maximize compressive strength of concrete



## Results

Inconclusive

So, the components as a percentage of total mixture was not the greatest input. This could be because of the non-Gaussian like distribution or a bad metric. Perhaps I should I change the Target to a classifier problem. There is a likely chance that leaving the target unchanged also impacted this approach.

The data in the kg in a M^3 mixture did "Better" but the models all overfit. I will have to keep tweaking the data and models.
