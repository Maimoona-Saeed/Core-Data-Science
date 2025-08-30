# Core-Data-Science
(we stan dr.mehdi)

# LoanGrant Dataset - Data Science Tasks

This project uses the dataset **loangrant.csv** and consists of two main parts: exploratory data analysis (EDA) and machine learning classification models.

## Data Dictionary
1. Loan ID – Unique identifier for loan information  
2. Customer ID – Unique identifier for customer (a customer may have multiple loans)  
3. Loan Status – Indicates if the loan was paid back or defaulted  
4. Current Loan Amount – The amount paid off or defaulted  
5. Term – Short term or long term loan  
6. Credit Score – Value between 0 and 800 indicating risk level  
7. Years in Current Job – How many years the customer has been in the current job  
8. Home Ownership – Rent, Home Mortgage, or Own  
9. Annual Income – Customer’s yearly income  
10. Purpose – Loan purpose description  
11. Monthly Debt – Monthly payment for existing loans  
12. Years of Credit History – Number of years since first credit entry  
13. Months Since Last Delinquent – Months since last delinquent payment  
14. Number of Open Accounts – Total open credit cards  
15. Number of Credit Problems – Recorded credit problems  
16. Current Credit Balance – Current total debt  
17. Maximum Open Credit – Maximum credit limit across all accounts  
18. Bankruptcies – Number of bankruptcies  
19. Tax Liens – Number of tax liens  

## Part A – Exploratory Data Analysis
- Perform EDA with histograms, scatter plots, boxplots, and missing value checks  
- Identify missing values and replace them with appropriate central tendency (mean, median, or mode) with justification  
- Detect outliers using boxplot and IQR method, report percentage of data with outliers, and replace appropriately  
- Perform correlation analysis and report attributes with correlation ≥ 0.6  
- Standardize the “Years in Current Job” attribute using the given format  
- Document code with explanations and include snapshots of graphs with descriptions in a compiled PDF  
- Submit Jupyter Notebook (named with Student ID) and PDF  

## Part B – Machine Learning Models
- Preprocess dataset (handle missing values, outliers, duplicate instances)  
- Apply classification models: Decision Tree, Bagging, Boosting, Random Forest, KNN, and SVM  
- Split dataset into 80% training and 20% testing  
- Generate confusion matrices for each model  
- Compute metrics: Accuracy, Sensitivity, Specificity, MCC, ROC curve plots  
- Write a comparative discussion (minimum 3 pages / ~1000 words)  
- Prepare slides for a 10-minute presentation  
- Record a video presentation (camera required except for female students; screen sharing mandatory)  
- Submit: Video, PDF (results + confusion matrices + discussion), Jupyter Notebook  

