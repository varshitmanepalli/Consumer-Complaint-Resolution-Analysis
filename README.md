# Consumer Complaint Resolution Analysis
This repository contains a Jupyter Notebook that explores the Consumer Complaint dataset to predict whether a consumer will dispute a complaint resolution. The project leverages various machine learning algorithms to build a predictive model that helps in understanding customer satisfaction and improving dispute resolution processes.

## Description
The analysis focuses on complaints registered by consumers regarding financial products. The goal is to predict whether a complaint will be disputed by the consumer, using data provided in the dataset which includes features like product type, issue, and company response.

## Dataset
The dataset is derived from a real-world data source and includes various attributes such as the type of product, the issue filed, the company's response, and whether the complaint was disputed by the consumer. The target variable is the dispute status, which is binary (Disputed/Not Disputed).

## Method
The notebook performs the following key operations:

* Data Preprocessing: Handling missing values, encoding categorical variables, and feature selection through PCA.
* Exploratory Data Analysis (EDA): Visual analysis of the different attributes and their impact on the dispute status.
* Model Building: Several models were built including Logistic Regression, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, KNeighbours, and XGBoost.
* Model Evaluation and Selection: The models are evaluated based on their accuracy, and the best-performing model is selected for making final predictions.

## Result
The analysis concludes with the selection of the best model based on validation accuracy. This model is then used to predict dispute status for a new set of test data. The final predictions are saved to an Excel file, aiding in decision-making processes for business operations.
