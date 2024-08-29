# Loan_eligibility_predective_analyser
This repository presents a comprehensive predictive analytics solution for determining loan eligibility, leveraging advanced machine learning techniques and data preprocessing methodologies. The project is implemented in Google Colab, utilizing a dataset from Kaggle's Loan Data repository, which encompasses a diverse range of attributes pertinent to creditworthiness assessment.

# Technical Specifications

*Programming Language: Python 3.x
*Libraries and Frameworks:
          Pandas for data manipulation and analysis
          NumPy for numerical computations
          Scikit-learn for machine learning model development and evaluation
          Matplotlib and Seaborn for data visualization
# Dataset

*Description: A comprehensive dataset comprising 615 observations and 13 features, including:
1)Loan ID
2)Gender
3)Married
4)Dependents
5)Education
6)Self_Employed
7)ApplicantIncome
8)CoapplicantIncome
9)LoanAmount
10)Loan_Amount_Term
11)Credit_History
12)Property_Area
13)Loan_Status

# Methodology
  Data Preprocessing:   
      Handling missing values using imputation techniques
      Encoding categorical variables via one-hot encoding
      Scaling/normalizing numerical features
  
  Feature Engineering:
      Extracting relevant features from existing attributes
      Creating interaction terms to capture complex relationships
  
  Model Development:
  Training and evaluating multiple machine learning models, including:
          * Logistic Regression
          * Decision Trees
          * Random Forest
          * Gradient Boosting

Model Evaluation:
       * Assessing performance using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC
       * Visualizing results via confusion matrices and ROC curves

Repository Structure
    * Loan_Eligibility_Predictive_Analyser.ipynb: The primary Google Colab notebook containing the project's code and documentation.
    * data: A directory containing the Loan Data dataset from Kaggle.
    * utils: A module providing supplementary functions for data preprocessing and visualization.
