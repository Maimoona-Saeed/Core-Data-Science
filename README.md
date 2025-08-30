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

## Task 1 – Exploratory Data Analysis
EDA was performed to understand the structure and quality of the dataset.  
- Histograms, scatter plots, and boxplots were used to visualize distributions and relationships.  
- Missing values were identified and imputed using mean, median, or mode with justification.  
- Outliers were detected using boxplots and the IQR method, and replaced appropriately (median in most cases).  
- Correlation analysis was conducted, with attributes above 0.6 correlation highlighted.  
- The “Years in Current Job” column was standardized into a consistent categorical format.  

## Task 2 – Machine Learning Models
Classification models were trained and evaluated on the processed dataset.  
- Models applied: Decision Tree, Bagging, Boosting, Random Forest, KNN, and Support Vector Machines.  
- The dataset was split into **80% training and 20% testing**.  
- Evaluation included confusion matrices, accuracy, sensitivity, specificity, Matthews Correlation Coefficient (MCC), and ROC curve plots.  
- Results were compared, with ensemble methods (Random Forest, Boosting) performing best overall.  


