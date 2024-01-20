# House Price Prediction

## Table of Contents:
* [Introduction](#introduction)
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Analysis Approach](#analysis-approach) 
* [Key Findings](#key-findings)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [References](#references)

## Introduction:  
<div align="justify">This repository contains the code and analysis for a assignment related to building a regression model for a US-based housing company, Surprise Housing, entering the Australian market, using data analytics to buy houses below market value and sell them at a profit. They've gathered Australian housing data in a CSV file and need a regression model with regularization to predict property values, aiding investment decisions. The company aims to identify significant variables influencing house prices, assess their impact, and determine optimal lambda values for ridge and lasso regression. In this repository contains two assignment parts:</div>

## Problem Statement:  
#### Part-I:
<div align="justify">
In this section, we will focus on building a regression model using regularization to predict house prices. The company aims to understand which variables are significant in predicting price of house and how well these variables describe the house prices. Additionally, we will determine the optimal values of lambda for ridge and lasso regression.

#### Part-II:
This section, includes specific questions related to the analysis made in Part-I. Each question is answered concisely.</div>

## Objectives:  
<div align="justify">The main objective is to create a model that predicts house prices based on the given independent variables. The management will use this model to analyze the variations in prices associated with these variables. This insight will enable them to adjust the firm's strategy, focusing on areas that promise higher returns. Further, the model serves as a valuable tool for the management to comprehend the pricing dynamics in a new market.</div>

## Analysis Approach:    
<div align="justify">To tackle this problem effectively, I have established a structured data analysis approach.<br>

- Data Preprocessing:<br> It includes understanding, cleaning, and preparing the data for analysis, handling missing values, encoding categorical variables, dropping unnecessary columns, and standardizing data.

- Exploratory Data Analysis (EDA):<br>Exploring the dataset to identify patterns, trends, and relationships in the dataset. This will involve univariate, and bivariate analysis.

- Feature Importance:<br>Identifying key variables that strongly influence target variables using statistical methods such as Exploratory Data Analysis (EDA).

- Feature Engineering:<br> It Explore opportunities for creating new features that might enhance model performance and transform variables to better suit the regression models.

- Visualizations:<br>It includes creating visual representations of the data to facilitate a better understanding of the insights, trends, and relationships.

- Model Building:<br>It includes splitting the data into training and testing sets, performing scaling, partition the data into features (X) and the target variable (Y) and performing Ridge and Lasso regression analysis on the dataset.

- Model Evaluation:<br>It includes evaluating, validating, comparing the performance of Ridge and Lasso Regression models and examining the R-squared values. And analyzing which model provides better insights into house price prediction.</div>

## Key Findings:
#### The variables significant in predicting the price of a house (Lasso predictors) are: - 
 - OverallQual_9
 - GrLivArea
 - OverallQual_8
 - Neighborhood_Crawfor
 - Exterior1st_BrkFace
 - Functional_Typ
 - CentralAir_Y
 - Neighborhood_Somerst
 - TotalBsmtSF
 - Condition1_Norm  
       
### The optimal value of lambda for Ridge Regression is 10 and the optimal value of lambda for Lasso is 0.001.

## Technologies Used:
- Python, version 3 
- NumPy for numerical computations
- Matplotlib and seaborn for data visualization
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Sklearn for machine learning tasks
- Jupyter Notebook for interactive analysis

## Acknowledgements:
- I acknowledge and appreciate the valuable course materials from upGrad and IIIT-B which enhanced my understanding of data analysis and machine learning

## References:
- Python documentations
- Exploratory Data Analysis
- Stack Overflow

## Contact:
Created by https://github.com/Erkhanal - feel free to contact!
