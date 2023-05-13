# Customer_Churn_Prediction

### Overview
This study focuses on customer churn in the telecom industry. Customer churn occurs when customers discontinue their business with a company or service provider. Retaining customers is challenging for firms with a large customer base, as individually attending to each customer's needs is cost-ineffective. However, by identifying potential churners in advance, companies can minimize wasted resources and improve customer retention in a partially cost-effective manner. Predicting customer churn not only helps maintain market performance and position but also facilitates business growth and expansion. The larger the customer base, the lower the cost of acquisition, and the higher the profit.

In this study, we analyze churn data from the telecom industry and aim to predict customers who are likely to discontinue their service. We utilize libraries such as scikit-learn, Matplotlib, pandas, seaborn, and NumPy.

### Problem Setting
The main objective is to build a predictive model that accurately identifies customers likely to churn or leave the telecom company. This will enable the company to take proactive measures to retain these customers and reduce the churn rate.

### Problem Definition
Telecom customer churn prediction is crucial in the telecommunications industry as it helps identify customers who are most likely to cancel their service or switch to a competitor. Churn can significantly impact a company's revenue. The goal of telecom customer churn prediction is to develop a model that accurately predicts which customers are at risk of churning so that the company can take proactive measures to retain them. Some of the tasks involved in this study are:

- Calculating the percentage of customers who churn and those who remain with active services.

- Analyzing the data considering various factors that contribute to customer churn.

- Selecting the best machine learning model to accurately classify churn and non-churn customers.


### Data Source
We utilized the Customer Churn Prediction dataset from Kaggle, which contains information about a telecommunication company's customers and their details. The dataset includes the following information:

- Customers who have left (churned).
- Services each customer has signed up for, such as phone, internet, etc.
- Customer account information, including tenure with the company and payment method.
- Demographic information, such as gender and age.

You can find the dataset at: [Customer Churn Prediction Dataset](https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction/input)

### Project Results
The project aimed to explore and analyze the telecom customer churn dataset and develop a classification model to predict customer churn in the telecom industry. The dataset contained information about various factors that may contribute to customer churn, such as gender, age, contract type, payment method, and others. a model to accurately predict churn.
The initial data exploration revealed that there were no missing values in the dataset, except for 11 missing records in the 'TotalCharges' column. These missing values were imputed using the mean value of the column. The correlation between different columns in the dataset was analyzed using a heatmap, which revealed a strong correlation between the 'tenure' and 'TotalCharges' columns, as expected.
Various data visualization techniques, including pie charts, bar plots, and histograms, were used to explore the dataset further. The visualization results showed that customers on a month-to-month contract basis had a higher churn rate as compared to others.
The project delivered a classification model with high accuracy in predicting customer churn. Several classification models were applied to the data to identify the one with the highest accuracy score. The accuracy of each model was calculated using K-fold cross- validation, with 10 splits. The metrics used were ROC AUC and accuracy score, with the results saved in a table for easier comparison. The logistic regression model was selected as the best model with an accuracy score of 86.9%. A plot of the logistic regression model scores versus the range of K values from 1 to 25 is also presented.
The key findings and deliverables of the project were that the majority of customers were on a month-to-month contract and paid their bills electronically. Additionally, the dataset was balanced, with approximately 27% of customers churning. The project delivered data exploration and visualization techniques that could be used by the telecom company to better understand the factors that contribute to customer churn and take necessary actions to retain customers. Also, understanding of the most important features that lead to churn and recommendations on how to improve customer retention. The model can be used to predict customer churn and identify customers who are at high risk of leaving, allowing the telecom company to take steps to retain them.


### Impact Of the Project Outcomes
The value created by our data mining effort in this project is significant in the sense that we were able to accurately predict which customers are at risk of churning and take proactive measures to retain them.
The machine learning models we developed were able to achieve high accuracy rates and true positive scores, especially the Logistic Regression model and the Linear Discriminant Analysis model. Through our data exploration and mining, we were able to identify the factors that contribute to client churn and perform necessary data preprocessing techniques such as imputation and feature scaling. Our analysis of the dataset using various performance metrics such as accuracy, precision, recall, and F1- score using a confusion matrix, and ROC graphical representation helped us to compare and evaluate the performance levels of each model to the problem statement in question.
The Logistic regression model with an accuracy score of 0.816 has proven to be the most accurate in predicting customer churn. The model also identifies the most important features that contribute to customer churn, such as contract type, payment method, and tenure. These insights can be used by the telecom company to take necessary actions to retain customers by offering more personalized services and incentives to customers who are at high risk of churning.
In addition, the association rules generated from the dataset can help the company identify patterns and relationships between different variables that may contribute to customer churn. For example, the association rule analysis may reveal that customers who have a month-to-month contract and pay their bills electronically are more likely to churn. Armed with this knowledge, the company can take action to address these issues and reduce the churn rate.
Overall, our data mining effort was able to generate valuable insights, patterns, and trends that can be used to improve customer retention rates in the telecommunications industry, resulting in a significant positive impact on the company's revenue.
