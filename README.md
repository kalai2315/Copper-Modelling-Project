<img width="743" alt="image" src="https://github.com/user-attachments/assets/0011a95e-9e7c-4637-93c4-9443c39edced"># Copper-Modelling-Project

**Project Description**

The Copper Modeling Project aims to develop predictive models for analyzing and forecasting copper prices. This project utilizes various machine learning techniques to process historical data and make accurate predictions. The outcomes of this project can help stakeholders make informed decisions in trading and investment.

**Problem Statement**
The copper industry often deals with issues such as skewness and noisy data, affecting manual pricing predictions. A machine learning regression model can address these issues by normalizing data, scaling features, and detecting outliers. Additionally, a lead classification model can help evaluate leads based on their likelihood of becoming customers, using the STATUS variable with WON as Success and LOST as Failure.

**Solution Steps**

**Exploring Skewness and Outliers:**

Use Seaborn’s boxplot, distplot, and violinplot to visualize and treat skewness and outliers.

**Data Preprocessing:**

**Clean and transform the data.**

Handle missing values, encode categorical variables, and scale features.
Drop highly correlated columns using a Seaborn heatmap.

**Feature Engineering:**

Create new features by transforming existing ones to make the data more informative.

**Model Building and Evaluation:**

Split data into training and testing sets.
Train regression models to predict Selling_Price.
Train classification models to predict Status (WON/LOST).
Evaluate models using appropriate metrics and optimize hyperparameters using cross-validation and grid search.

**Streamlit GUI:**

Create an interactive page to input column values and get predictions for Selling_Price or Status.
Use the pickle module to save and load models, encoders, and scalers.
<img width="707" alt="image" src="https://github.com/user-attachments/assets/2dfb864f-8d8f-4462-8329-1d71747d305d">





