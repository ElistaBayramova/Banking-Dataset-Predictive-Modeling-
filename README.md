# Banking-Dataset-Predictive-Modeling-
The problem is to identify potential clients beforehand that will subscribe to the term deposits of the bank. 
The goal of this project is to build a model to predict if the client will subscribe to a term deposit
Data source: https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets

Step 1. Exploratory Data Analysis  
- Checking Duplicate Rows
- Checking Missing Values
- Handling Outliers by using Interquartile Range
- Removing Unnecessary Features ('previous', 'pdays’,‘day of week', 'month' )
- Data Visualization 
- Encoding Categorical Data by using Label Encoder
  
Step 2. Data Preparation for Modeling
- Splitting Data into Train and Test Data
- Handling Imbalance Problem
- Scaling Data for Handling Skewness
- K-fold Cross Validation

Step 3. Model Selection  
6 Machine Learning algorithms (Logistic Regression, Decision Tree Classifier, SVM, KNN, XGBoost Classifier, Random Forest Classifier) were tested.
Random Forest showed the best performance.   

Step 4. Model Improvement  
- Hyperparameter Tuning using Grid Search
- Feature Selection using Feature Importance of Random Forest Classifier Model (‘housing’ and ‘loan’ features that were not important for the model were removed)

Step 5. Model Building with best parameters and top features





  




 






