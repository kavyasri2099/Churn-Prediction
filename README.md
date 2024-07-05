# Churn-Prediction  

Project Overview:  
This project aims to predict customer churn using various machine learning algorithms. The dataset includes customer information such as tenure, monthly charges, and total charges, among other features. The goal is to identify customers who are likely to cancel their subscription based on these features.  
  
Dataset:  
The dataset used in this project is churn_dataset.csv. It contains the following columns:  
  
customerID  
gender  
SeniorCitizen  
Partner  
Dependents  
tenure  
PhoneService  
MultipleLines  
InternetService  
OnlineSecurity  
OnlineBackup  
DeviceProtection  
TechSupport  
StreamingTV  
StreamingMovies  
Contract  
PaperlessBilling  
PaymentMethod  
MonthlyCharges  
TotalCharges  
Churn  

You can install the required libraries using the following command:  

pip install numpy pandas seaborn matplotlib scikit-learn  
Data Preprocessing  

Loading the Data: The dataset is loaded using pandas.  
Handling Missing Values: The TotalCharges column contains some missing values which are replaced with the median of the column after converting it to numeric.  
Splitting the Data: The dataset is split into training and testing sets (75:25 ratio).  

Feature Transformation  
Numerical Features: StandardScaler is used to standardize the numerical features.   
Categorical Features: OneHotEncoder is used to encode categorical features.  
Model Training and Evaluation  

The following machine learning models were trained and evaluated:  
  
Logistic Regression  
K-Nearest Neighbors (KNN)  
Support Vector Machine (SVM)  
Decision Tree  
Random Forest  
Accuracy scores for each model were calculated and compared.  

Results  
The accuracy of each model is as follows:  

Logistic Regression: 81.26%  
K-Nearest Neighbors: 76.83%  
Support Vector Machine: 80.46%  
Decision Tree: 71.77%  
Random Forest: 78.81%  

Files  
churn_dataset.csv: The dataset used for this project.  
churn_prediction.ipynb: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.  
churn_prediction_presentation.pptx: PowerPoint presentation summarizing the project.  
  
Conclusion  
This project demonstrates the use of various machine learning algorithms to predict customer churn. The results show that the Logistic Regression model achieved the highest accuracy of 81.26% . This model can be used to identify customers at risk of churn and take proactive measures to retain them.  

