# Retail-Sales-Prediction
Problem Statement and Project Description
Retail Sales Prediction is a regression machine learning project. Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.
Businesses use sales forecasts to determine what revenue they will be generating in a particular timespan to empower themselves with powerful and strategic business plans. Important decisions such as budgets, hiring, incentives, goals, acquisitions and various other growth plans are affected by the revenue the company is going to make in the coming months and for these plans to be as effective as they are planned to be it is important for these forecasts to also be as good.
The work here forecasts the sales of the various Rossmann stores across Europe for the recent six weeks and compares the results from the models developed with the actual sales values.
Project Summary
The Rossman Sales Prediction project involved extensive data analysis, feature engineering, and model selection to accurately forecast sales. Here is a brief overview of the project steps and key findings:

Data Gathering and Cleaning:

Collected historical sales data for Rossmann stores, including competitor details, holidays, customer count, and daily sales.
Performed data cleaning to handle missing values and ensure data consistency.
Merged relevant datasets to enhance the feature set.
Exploratory Data Analysis (EDA):

Conducted in-depth EDA by exploring univariate, bivariate, and multivariate relationships.
Generated insightful visualizations to uncover patterns and trends in the data.
Extracted meaningful insights to inform future decision-making in the machine learning pipeline.
Feature Engineering and Preprocessing:

Created additional features such as PromoDuration and CompetitionDuration to capture relevant information.
Addressed multicollinearity among independent variables using variance inflation factor (VIF) analysis.
Detected and treated outliers using the Interquartile Range (IQR) technique.
Encoded categorical variables using One-Hot Encoding for compatibility with machine learning algorithms.
Applied various transformation techniques to achieve normal distribution of data.
Model Selection and Training:

Split the preprocessed data into training and testing sets.
Utilized a variety of machine learning algorithms, including linear regression, decision trees, random forests, LightGBM, and XGBoost.
Evaluated model performance using metrics such as R-squared score, accuracy, and mean absolute percentage error (MAPE).
Employed regularization techniques (e.g., Lasso, Ridge, Elastic Net) for improved model performance.
Identified XGBoost as the optimal model due to its high accuracy, with an MAPE of only 2% and an R-squared score of 0.94.
Model Deployment and Conclusion:

Finalized the XGBoost model for deployment, as it demonstrated the highest accuracy and the least error.
Developed a comprehensive machine learning pipeline that combines data processing, feature engineering, and model evaluation.
Successfully created a model capable of accurately predicting sales for Rossmann stores up to six weeks in advance.
This project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. The insights gained from the analysis provide valuable information for decision-making within the retail industry.
