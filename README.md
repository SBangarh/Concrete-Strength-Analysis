# Concrete-Strength-Analysis

## Data
source : https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

## Purpose
To predict the Compressive Strength based on input variables without using Neural Networks.

## Process

I started with EDA exploring the variables and their relationships. There was a lot of non linear relationships in the data.
At first, I just focused on the raw data and composition of the features (Kg in m^3 mixture), but pivoted to a percentage of total mixture with the exception of Age and Compressive Strength.

I wanted to focus on "less" complex models than neural networks as I am still learning and want to get the basics down. Eventually, I would like to explore neural networks to answer how to maximize compressive strength of concrete

I initially explored ensemble methods as I though they'd pick up on relations better and that there no clear linear relationships. EDA showed that there was a lot of correlation among input vairables and this was a hint to explore dimensionality reduction (eg PCA).

Once I discovered a model that worked, I began trying to optimize the model for better results.



## Results

So far, the "best" model is a Ridge Regression (alpha=0.01) with PCA. The model had a R2 value of 0.48 on training data and 0.51 on testing data which isn't great, but it showed better results than the ensemble methods. The best results were achieved with three principal components. 

Still lots of work to do and adding to the model to increase fit.

