# Wine Quality Prediction Model
This repository contains the implementation of a machine learning model to predict the quality of wine based on various chemical properties. The project involves data preprocessing, exploratory data analysis (EDA), and model building using Linear Regression and Random Forest algorithms.

# Introduction
Wine quality is determined by various chemical properties. This project aims to predict wine quality using these properties with the help of machine learning models. We perform exploratory data analysis to understand the data and build predictive models to estimate wine quality.

#Dataset
The dataset used in this project is the Wine Quality dataset, which contains the chemical properties of different wines along with their quality ratings.

**File: WineQT.csv**\
**Attributes:**\
Fixed Acidity\
Volatile Acidity\
Citric Acid\
Residual Sugar\
Chlorides\
Free Sulfur Dioxide\
Total Sulfur Dioxide\
Density\
pH\
Sulphates\
Alcohol\
Quality (target variable)\
Exploratory Data Analysis\

**EDA is performed to gain insights into the dataset, identify patterns, and visualize relationships between features. Key steps include:**\

Distribution of wine quality\
Correlation analysis between features\
Relationship between acidity and pH level\
Outlier detection using Z-Score and IQR methods

**Model Building**
**Linear Regression**\
**Linear Regression** is used to model the relationship between the target variable and the independent variables.\
**Random Forest**\
**Random Forest** is an ensemble learning method that combines multiple decision trees to improve accuracy and control overfitting.
**Principal Component Analysis**\
PCA is used to reduce the dimensionality of the dataset while retaining most of the variance.

**Contributing**
Contributions are welcome! Please fork this repository and submit a pull request with your improvements or bug fixes.
