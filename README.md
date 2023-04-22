# 💳 Loan Credit and Risk Analysis

Applying Exploratory Data Analysis to find the driving factors that could lead to potential defaults or
finding the pattern among variables indicating if the applicant would default the loan. Moreover, this 
EDA will ensure that applicants who are capable of repaying the loans are not rejected.

## Index
- Problem Statement
- Section 1: Data sourcing and Understanding
    - current application data type and structure
    - previous application data type and structure
- Section 2: Data cleaning
    - Current application
    - Data types and null values calculation
    - Fixing rows and columns
    - Impute or remove missing values
    - Handling Outliers
    - Standardising values
    - Fixing Invalid values and filter data
    - Previous application
    - Data types and null values calculation
    - Fixing rows and columns
    - Impute or remove missing values
    - Handling Outliers
    - Standardising values
    - Fixing Invalid values and filter data
- Section 3: Analysis
    - Current application
    - Univariate Analysis
    - Bivariate/Multivariate Analysis
    - Merged dataset Analysis
    - Univariate Analysis
    - Bivariate/Multivariate Analysis
- Section 4: Outcomes

## Problem Statement

Loan providing company hesitates to provide loan to people who have either no or poor credit history. And there are two risk factors involved here:
- Company will lose the business if they rejects the potential customers, who are capable of repaying
    the loan.
- The company will face financial loses if they sanction the loan to the potential defaulters or applicants
    who likely to default the loan.

Given the data, target is to perform end to end EDA to ensure that applicants who are capable of repaying the loan are not rejected. The inferred knowledge from this EDA would help the loan company for its portfolio and risk assessment. Moreover to lower the potential default. 
    
The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios:

- The client having payment difficulties: applicant had late payments for more than X number of days
- All other cases: All other cases when the payment is paid on time.

There are four types of decision, when it comes to application.
- Approved: The Company has approved loan Application
- Cancelled: The client cancelled the application sometime during approval.
- Refused: Rejection from company for a loan application.
- Unused offer:  client cancelled the loan but during different stage of the process.

## Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
