# Concrete-Strength-Analysis

## Data
source : https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

## Purpose
To predict the Compressive Strength based on input variables without using Neural Networks; I prefer less complex models.

## Process

I started with EDA exploring the variables and their relationships. There was a lot of non linear relationships in the data.
At first, I just focused on the raw data and composition of the features (Kg in m^3 mixture), but pivoted to a percentage of total mixture with the exception of Age and Compressive Strength.

I used cross validation to guide which model I chose prior to optimizing. The raw data seemed to perform better on RandomForestRegressor than Linear Regression

## Results


