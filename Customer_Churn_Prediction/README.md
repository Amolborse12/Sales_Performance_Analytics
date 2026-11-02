Customer Churn Prediction Analysis

Project Overview

This project analyses customer data to identify patterns associated with customer churn and builds a machine learning model to predict customers who may leave a business.

Business Objective

- Analyse customer churn patterns.
- Identify factors associated with customer attrition.
- Prepare and clean customer data.
- Build and evaluate a churn prediction model.
- Support data-driven customer retention decisions.

Tools & Technologies

- Python
- Pandas
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Scikit-learn
- Logistic Regression
- Matplotlib

Project Workflow

1. Imported and inspected the customer dataset.
2. Cleaned and prepared the data.
3. Performed exploratory data analysis.
4. Split the data into training and testing sets (80:20).
5. Built a Logistic Regression model.
6. Evaluated model performance using classification metrics.
7. Applied class balancing to improve churn detection.

Model Results

Metric| Initial Model| Balanced Model
Accuracy| 61.5%| 63%
Churn Precision| 44.26%| 48.31%
Churn Recall| 38.57%| 81.43%
Churn F1-score| 41.22%| 61%

Key Findings

- Class balancing improved the model's ability to identify customers likely to churn.
- Churn recall increased from approximately 38.57% to 81.43%.
- The balanced model achieved approximately 63% accuracy.
- The model demonstrates how predictive analytics can support customer retention strategies.

Project Files

- "Day40_Customer_Churn_Analysis.ipynb" — data cleaning and analysis.
- "Day40_Customer_Churn_Cleaned.csv" — cleaned dataset.
- "Day41_Customer_Churn_Prediction.ipynb" — prediction model.
- "Day41_Customer_Churn_Predictions.csv" — prediction results.

Note

This is a portfolio project using practice data to demonstrate data analysis and machine learning skills. Results are based on the available dataset and should not be interpreted as guaranteed business outcomes.
