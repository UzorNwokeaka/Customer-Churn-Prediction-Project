# Customer-Churn-Prediction-Project
A customer churn machine learning prediction model which will help reduce customer attrition, enhance customer loyalty and ensure Connecttel maintains a solid edge in the highly dynamic &amp; competitive telecommunication industry. 

Customer-Churn-Prediction-Project

In this project, I analyzed, classified and predicted churn customers for a telecoms company using various algorithms under supervised machine learning. 

## Resources 

•	Data Source: Data of a global telecommunications company containing 7,043 records and 21 features. 

•	Python version: 3.11.4

•	Libraries: numpy, pandas, matplotlib, seaborn, sklearn

## Data Cleaning

•	Converted irregularities (‘ & ‘ ‘) to NaN

•	Converted NaN values to mean values under the TotalCharges feature

•	Converted TotalCharges feature from object to int. 

## Feature Engineering 

•	Performed feature extraction by dropping-off unwanted features – CustomerID, Churn, SeniorCitizens_Group, Tenure_Group

•	Performed feature construction by creating a new numeric feature – Churn_Type

•	Performed feature selection by selecting and converting all categorical features to numeric with exception of the five features above 

•	Performed feature scaling using the labelEncoder function as well as normalization by employing the MinMaxScaler function.

## Modeling 

•	Built eight (8) models and selected the top performing four (4) models.
•	In line with project outcome, I selected the best performing model out of the top four because of the required metrics for the business – Precision & Recall scores. 


Some Insights from the EDA

 ![output_94_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project/assets/128752357/8615781b-727e-461b-a172-e007188b009e)


 ![output_98_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project/assets/128752357/4efaeea4-dae3-44e7-817b-2c3e85601f3e)


![output_52_1](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project/assets/128752357/efa6151b-9c76-47c7-88a0-8a675e9f3ca8)

 
![output_115_0](https://github.com/UzorNwokeaka/Customer-Churn-Prediction-Project/assets/128752357/288bef62-3579-4e69-9067-961d85db4a53)

 
