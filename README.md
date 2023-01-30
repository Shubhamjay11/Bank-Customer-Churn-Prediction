# Bank Customer Churn Prediction

## Overview
This project aims to predict customer churn for a bank, using demographic information, customer behavior, and whether or not the customer has churned. The dataset used in this project is from the UCI Machine Learning Repository and can be found here.
link: https://www.kaggle.com/competitions/bank-marketing-uci/overview

## Tools and Technologies
Python  
Pandas  
Matplotlib  
Seaborn  
Sklearn   

## Methodology

The following steps were performed in this project:

Data Exploration and Cleaning   
Exploratory Data Analysis and Feature Selection   
Model Building   
Model Evaluation   
Fine-Tuning   

Multiple machine learning algorithms were used to build the predictive model including Logistic Regression, Random Forest, Gradient Boosting, Ridge Classifier, and Neural Classifier. The performance of these algorithms was evaluated using various metrics such as accuracy, precision, recall, F1-score and AUC-ROC. Gradient Boosting was found to be the best algorithm with the highest ROC AUC and MCC value.

## Result
Gradient Boosting performed the best among all the algorithms, with the highest ROC AUC and MCC score of 0.481. The results of other algorithms are:

Random Forest: MCC score of 0.460   
Logistic Regression: MCC score of 0.437    
Ridge Classifier: MCC score of 0.426   
Neural Classifier: MCC score of 0.372

![image](https://user-images.githubusercontent.com/116708200/215398707-8065b0ac-2101-42a2-9113-6757a54703ea.png)

![image](https://user-images.githubusercontent.com/116708200/215398634-71121920-988d-4707-9e5b-74b268230a24.png)



## Limitations and Possible Future Work
The model is based on a single dataset and may not generalize well to other datasets. In order to overcome this limitation, it would be beneficial to test the model on a larger and more diverse dataset. Additionally, other machine learning algorithms and techniques such as deep learning could be explored to improve the performance of the model.

## How to Use
-- Clone the repository   
--Install the required libraries using pip install -r requirements.txt   
--Run the Jupyter Notebook Bank_Customer_Churn_Prediction.ipynb

## Contributing
If you would like to contribute to this project, please reach out to me through the repository.
