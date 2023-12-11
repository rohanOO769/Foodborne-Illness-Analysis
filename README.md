# Foodborne-Illness-Analysis
This project focuses on analyzing and understanding foodborne illness outbreaks in the USA between 1998 and 2015. It includes exploratory data analysis, correlation analysis, and a linear regression model to predict outbreaks based on illnesses.

## Overview
Foodborne illnesses are a significant concern globally, impacting public health. This analysis delves into the dataset to extract insights into the outbreaks, their causes, associated factors, and potential predictive models.

## Table of Contents
Dataset
Exploratory Data Analysis
Correlation Analysis
Linear Regression Model
Usage
Contributing
License
Dataset
The dataset used in this analysis comprises foodborne illness outbreaks reported in the USA from 1998 to 2015. It includes information on illnesses, hospitalizations, fatalities, specific foods, ingredients, locations, and contaminants associated with the outbreaks. Additionally, it integrates meat consumption data during the same period.

## Exploratory Data Analysis
The analysis begins with data cleaning, handling missing values, and preparing the dataset for analysis. Key steps in the EDA include:

Outbreak Analysis: Grouping data by year to understand trends in outbreaks, illnesses, hospitalizations, and fatalities.
Meat Consumption Analysis: Aligning meat consumption data with outbreak data by year to explore correlations.
Visualizations: Utilizing Matplotlib and Seaborn to create visual representations for a better understanding of the dataset.
Correlation Analysis
Calculating correlation coefficients between different variables (outbreaks, illnesses, hospitalizations, fatalities, meat consumption) to identify relationships and dependencies among these factors.

## Linear Regression Model
Building a simple linear regression model using sklearn to predict outbreaks based on illnesses. The model's performance is assessed, and predictions are made using the trained model.
