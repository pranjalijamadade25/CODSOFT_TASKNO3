# Customer Churn Prediction

## Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a company based on customer information and behavior.

The project uses the Churn Modelling dataset and compares three Machine Learning algorithms:

- Logistic Regression
- Random Forest
- Gradient Boosting

## Dataset

The dataset contains 10,000 customer records with information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership Status
- Estimated Salary

The target variable is `Exited`.

- `0` = Customer stayed
- `1` = Customer exited

## Project Workflow

1. Load the dataset
2. Explore the data
3. Check missing values and duplicates
4. Perform exploratory data analysis
5. Remove unnecessary columns
6. Encode categorical features
7. Scale numerical features
8. Split data into training and testing sets
9. Train Machine Learning models
10. Evaluate the models
11. Select the best-performing model
12. Save the trained model
13. Predict churn for a new customer

## Machine Learning Models

### Logistic Regression
Used as a baseline classification model.

### Random Forest
An ensemble learning algorithm that combines multiple decision trees.

### Gradient Boosting
An ensemble technique that builds models sequentially to improve prediction performance.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Best Model

The best model is selected based on the highest F1 Score.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Files

- `customer_churn_prediction.ipynb` - Complete Jupyter Notebook
- `customer_churn_model.pkl` - Trained best model
- `model_comparison.csv` - Model performance comparison
- `new_customer_prediction.csv` - Sample prediction
- `project_summary.json` - Project performance summary
- `requirements.txt` - Required Python libraries

## Sample Prediction

The trained model can predict whether a new customer is likely to churn and also provide the probability of churn.

## Conclusion

This project demonstrates how Machine Learning can be used to identify customers who are likely to churn. Such predictions can help businesses identify at-risk customers and take suitable retention actions.
