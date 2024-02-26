# Concrete-Strength-Analysis

## Data
source : https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength

## Purpose
To predict the Compressive Strength based on input variables without using Neural Networks.

## Process

I started with EDA exploring the variables and their relationships. There was a lot of non linear relationships in the data.
At first, I just focused on the raw data and composition of the features (Kg in m^3 mixture), but perhaps a percentage of total mixture is worth exploring and perhaps more indicative of strength than a scalar value.

I wanted to focus on "less" complex models than neural networks as I am still learning and want to get the basics down. Eventually, I would like to explore neural networks to answer how to maximize compressive strength of concrete

I initially explored ensemble methods as I though they'd pick up on relations better and that there no clear linear relationships. EDA showed that there was a lot of correlation among input vairables and this was a hint to explore dimensionality reduction (eg PCA). 


## Results

So far, the "best" model is a Ridge Regression with PCA. Still lot's of work to do.
