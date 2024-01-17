# Customer Churn

## Overview:
This project focuses on analyzing customer churn in a telecom company named "Neo." The goal is to gain insights from the data and devise strategies to reduce customer attrition. The dataset used for this analysis is named `customer_churn`, and it contains information about various aspects of customer interactions with the telecom services.

## Tasks Performed:

### 1. Data Manipulation:
- Extracted the 5th and 15th columns, stored in variables `customer_5` and `customer_15`.
- Filtered male senior citizens with electronic check payment method, stored in `senior_male_electronic`.
- Extracted customers with tenure > 70 months or monthly charges > $100, stored in `customer_total_tenure`.
- Filtered customers with a two-year contract, mailed check payment method, and churn 'Yes', stored in `two_mail_yes`.
- Extracted 333 random records from the dataset, stored in `customer_333`.
- Obtained the count of different levels from the 'Churn' column.

### 2. Data Visualization:
- Built a bar plot for the 'InternetService' column to visualize its distribution.
- Constructed a histogram for the 'tenure' column with specified bin settings.
- Created a scatter plot between 'MonthlyCharges' and 'tenure' and a box plot for 'tenure' vs. 'Contract'.

### 3. Linear Regression:
- Built a simple linear model with 'MonthlyCharges' as the dependent variable and 'tenure' as the independent variable.
- Divided the dataset into a 70:30 train-test split.
- Predicted values on the test set, calculated root mean square error, and stored the result.

### 4. Logistic Regression:
- Built a simple logistic regression model with 'Churn' as the dependent variable and 'MonthlyCharges' as the independent variable.
- Split the dataset into a 65:35 train-test ratio, built the model, and evaluated accuracy using a confusion matrix.
- Extended to a multiple logistic regression model with 'tenure' and 'MonthlyCharges' as independent variables.
- Divided the dataset into an 80:20 train-test split, built the model, and assessed accuracy.

### 5. Decision Tree:
- Constructed a decision tree model with 'Churn' as the dependent variable and 'tenure' as the independent variable.
- Split the dataset into an 80:20 train-test ratio, built the model, and calculated accuracy using a confusion matrix.

### 6. Random Forest:
- Implemented a Random Forest model with 'Churn' as the dependent variable and 'tenure' and 'MonthlyCharges' as independent variables.
- Divided the dataset into a 70:30 train-test ratio, built the model, and evaluated accuracy using a confusion matrix.

## Conclusion:
The project involves a comprehensive analysis of customer churn, incorporating data manipulation, visualization, and various machine learning models. These models are essential for predicting and understanding customer behavior, allowing the telecom company to take proactive measures to retain its customer base. The results and insights obtained from this analysis can guide strategic decision-making to reduce customer churn.
