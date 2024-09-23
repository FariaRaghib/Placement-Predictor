# Placement Predictor
This project aims to predict the placement status of students based on their IQ and CGPA using a logistic regression model. We used a dataset of 100 students, which includes information about their IQ, CGPA, and whether they were placed or not. The goal was to preprocess the data, build a predictive model, and eventually deploy the model for practical use.

# Project Steps
## 1. Data Preprocessing + EDA + Feature Selection
Data Cleaning: Handled missing values and outliers.
Exploratory Data Analysis (EDA): Conducted analysis on IQ, CGPA, and placement status to understand trends and distributions.
Feature Selection: Selected IQ and CGPA as key features based on their correlation with placement status.
## 2. Extract Input and Output
Input Features: IQ, CGPA
Output Variable: Placement status (0 = Not Placed, 1 = Placed)
## 3. Train Test Split
Split the data into training and testing sets.
Test size: 10% of the dataset was kept for testing purposes.
## 4. Model Training
We used Logistic Regression as the predictive model for binary classification (placement vs. non-placement).
Training dataset: 90% of the data was used to train the model.
## 5. Model Evaluation
Evaluated the model on the test data to assess its performance.
Key metrics include accuracy, precision, recall, and F1-score.
## 6. Model Deployment (In Progress)
The model has been exported using pickle for future deployment.
Full deployment on a live server or web application is pending.
# Dependencies
Python (3.x)
Pandas
NumPy
Scikit-learn
Pickle
# Future Improvements
Complete the deployment phase (web or cloud-based deployment).
Explore advanced models such as Random Forest or SVM to improve prediction accuracy.
