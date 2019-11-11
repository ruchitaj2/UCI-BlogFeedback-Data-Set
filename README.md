# UCL Machine Learning dataset - BlogFeedback

## Overview
This project performs a feature and model selection on the UCI machine learning BlogFeedback dataset. 
The methods used include ridge, lasso, and least square regressions. Given the performance metrics, 66 features are selected from 280 features via Lasso regression.

## Data Description
Detailed documentation and data source are available here UCL - BlogFeedback Data Set
Original Dataset Link: https://archive.ics.uci.edu/ml/datasets/BlogFeedback

The dataset include 281 variables (280 features and 1 target variable). The data-attribute-description.md describe the names of the features which correspond to the columns of the dataset.

The original dataset includes one train set, blogData_train.csv and multiple small test set. 
I have performed testing on 'blogData test-2012.03.31.01 00.cs'. All analysis are based on the blogData_train.csv and test.csv.

## Procedure of analysis
To reproduce the whole analysis, you need to clone the repo into your local machine.

Then open the jupyter notebook in src/analysis-script.ipynb, and run all from top to bottom.


## Dependencies
Python - 3.6
Jupyter notebook - 1.0.0
Numpy - 1.13.3
Pandas - 0.22.0
matplotlib - 2.1.1
scikit-learn - 0.19.1

## Instructions for running program:

1. The corresponding codes are in .ipnyb format which requires Jupyter notebook.  
2. Make sure the dataset required is in the same folder path as the .ipnyb file.  
3. For Question 1    
Train:  Data  blogData_train.csv  
Test:  Data blogData_test-2012.03.31.01_00.csv  
4. Please run the blocks sequentially.  
