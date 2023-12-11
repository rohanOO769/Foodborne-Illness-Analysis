# Foodborne-Illness-Analysis
This project focuses on analyzing and understanding foodborne illness outbreaks in the USA between 1998 and 2015. It includes exploratory data analysis, correlation analysis, and a linear regression model to predict outbreaks based on illnesses.

## Overview
Foodborne illnesses are a significant concern globally, impacting public health. This analysis delves into the dataset to extract insights into the outbreaks, their causes, associated factors, and potential predictive models.

## Dataset
The dataset used in this analysis contains detailed records of foodborne illness outbreaks reported in the USA from 1998 to 2015. It encompasses a wide range of information, including the number of illnesses, hospitalizations, fatalities, specific food items, contributing factors, locations, and contaminants associated with each outbreak. Additionally, it integrates data on meat consumption during the same period.

## Exploratory Data Analysis
The analysis initiates with meticulous data cleaning procedures aimed at handling missing values, ensuring data consistency, and preparing the dataset for in-depth analysis. Key steps involved in the exploratory phase include:

### Outbreak Analysis: 
Aggregating and summarizing data by year to discern trends in the number of outbreaks, illnesses, hospitalizations, and fatalities.
### Meat Consumption Analysis: 
Correlating meat consumption data with outbreak statistics by aligning both datasets temporally to identify potential associations.
### Visualizations: 
Utilizing Matplotlib and Seaborn libraries to create visual representations, including line plots, bar graphs, and heatmaps, aiding in the intuitive understanding of the dataset.

## Correlation Analysis
Conducting correlation analysis to quantify relationships between various factors such as outbreaks, illnesses, hospitalizations, fatalities, and meat consumption. This step aims to identify significant correlations and dependencies among these variables.

## Linear Regression Model
Developing a simple linear regression model using the scikit-learn library to predict outbreaks based on the number of reported illnesses. The model's accuracy and predictive capabilities are assessed and demonstrated by making predictions using the trained model.
