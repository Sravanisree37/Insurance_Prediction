# Insurance_Prediction
Built a regression model, that predicts the optimum health insurance cost of an individual using health  and habit related parameters, with R-squared value (R2) as high as 92%.

**Introduction**
	In machine learning, regression helps in the mapping of a predictive relationship between labels and data points. Regression algorithms are used in Machine Learning to predict future values. Regression is used to make a wide range of future value predictions using the input data and historical data. Regression helps in defining the relationship between label and data points, which is the target variable (to be predicted) in machine learning.  
**Problem Definition**
	The goal of this project is to build a regression model, that predicts the optimum health insurance cost of an individual using health and habit related parameters, with R-squared value (R2) as high as 95%. The data set used is adopted from Kaggle (open-source website).
**Predictive Model Selection**
  Dataset
	The dataset used for this project has been adopted from Kaggle (https://www.kaggle.com/datasets/gdeepakreddy/insurance) website. This dataset contains 23 attributes all are related to different health and physical fitness parameters.

**Data Analysis**
An exploratory data analysis has been performed on this dataset. After which several levels of categorical data have been clubbed together. All the attributes that contain null values have been either removed or the null values have been replaced with mean of that column. Then a correlation matrix has been constructed and the attributes that have 0 correlation to the target attribute have been removed from the dataset. 

**Model Training**
	First the dataset has been divided into train , validate and test data with the ratio of 8:1:1 respectively. Now six regression algorithms namely Multi-Linear Regression, Support Vector Machine, Lasso Regression, Decision Tree Regression, Random Forest Regression and Ridge Regression have been trained on the train data and tested on validation data. 

