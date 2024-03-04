![image](https://github.com/Basavarajgulabal/Retail-sales-prediction/assets/121421909/911c0c0e-9ba9-4226-916e-84f7f3364c26)








Rossman Sales Prediction



This repository contains the code and documentation for the Rossman Sales Prediction project. The goal of this project is to forecast the daily sales of Rossmann stores for up to six weeks in advance. By accurately predicting sales, store managers can make informed decisions regarding promotions, competition, holidays, and other factors that influence sales performance.


Problem Statement


Rossmann operates over 3,000 drug stores across 7 European countries. Currently, store managers rely on their own predictions for daily sales, leading to varying levels of accuracy. The objective of this project is to develop a machine learning model that can forecast the "Sales" column for the test set. The dataset provided includes historical sales data for 1,115 Rossmann stores, taking into account factors such as promotions, competition, school and state holidays, seasonality, and store locality. It is worth noting that some stores in the dataset were temporarily closed for refurbishment.

Project Summary


The Rossman Sales Prediction project involved extensive data analysis, feature engineering, and model selection to accurately forecast sales. Here is a brief overview of the project steps and key findings:

Data Gathering and Cleaning:

1-Collected historical sales data for Rossmann stores, including competitor details, holidays, customer count, and daily sales.

2-Performed data cleaning to handle missing values and ensure data consistency.

3-Merged relevant datasets to enhance the feature set.



Exploratory Data Analysis (EDA):

1-Conducted in-depth EDA by exploring univariate, bivariate, and multivariate relationships.

2-Generated insightful visualizations to uncover patterns and trends in the data.

3-Extracted meaningful insights to inform future decision-making in the machine learning pipeline.



Feature Engineering and Preprocessing:

1-Created additional features such as PromoDuration and CompetitionDuration to capture relevant information.

2-Addressed multicollinearity among independent variables using variance inflation factor (VIF) analysis.

3-Detected and treated outliers using the Interquartile Range (IQR) technique.

4-Encoded categorical variables using One-Hot Encoding for compatibility with machine learning algorithms.

5-Applied various transformation techniques to achieve normal distribution of data.



Model Selection and Training:

1-Split the preprocessed data into training and testing sets.

2-Utilized a variety of machine learning algorithms, including linear regression, decision trees, random forests and XGBoost.

3-Evaluated model performance using metrics such as R-squared score, accuracy, and mean absolute percentage error (MAPE).

4-Employed regularization techniques (e.g., Lasso, Ridge, Elastic Net) for improved model performance.

5-Identified XGBoost as the optimal model due to its high accuracy, with an MAPE of only 2% and an R-squared score of 0.94.



Model Deployment and Conclusion:

1-Finalized the XGBoost model for deployment, as it demonstrated the highest accuracy and the least error.

2-Developed a comprehensive machine learning pipeline that combines data processing, feature engineering, and model evaluation.

3-Successfully created a model capable of accurately predicting sales for Rossmann stores up to six weeks in advance.

This project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. The insights gained from the analysis provide valuable information for decision-making within the retail industry.

