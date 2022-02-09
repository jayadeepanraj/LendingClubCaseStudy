# Lending Club Case Study
> Need to identify the driving factors/variables for Loan default based on the provided data set
Approach using techinques such as Data Understanding - Getting insight on the dataset provided and its variables along with the nature of data, Data Cleaning - Data that cannot be utilized to be cleaned by removing null columns and rows that can be removed safely, Data Handling - Data type conversion and changing the values to usable form, Data Analysis - Performing Univariate, Bivariate and Multivariate analysis and finally a recommendation - Based on the analysis recommendations to reduce Loan default to be suggested


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Lending Club Case Study - Need to identify the driving factors/variables for Loan default based on the provided data set
- Lending Club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. 
- Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- Loan dataset that contains the complete loan data for all loans issued through the time period 2007 t0 2011 to be used for analysis.

## Conclusions
- Debt to Income Ratio is major driver for default and above 20 has very high value loans charged off hence it is recommended to not to grant loans above dti ratio of 20.
- Home Owners with Mortgage default the high value loans with are around 30% of charge-off comprises of high value. Hence it is recommended to reduce the funded amount by investor to the requested loan amount.
- Low Income Group has most number of default and Poor Income group has the highest ratio of default to paid with DTI to default observation of very high default above 15 hence it is recommended to grant loans with debt to income ratio of less than 15 and whose income is not verified to Low and Middle income group to reduce default.
- Employees with less than 3 years of experience who has verified Income to be granted loans since this category has most number of default.
- Credit card, Debt consolidation and small business purposes to granted loans of DTI less than 15 since above that ratio very high value loans are defaulted.
- Borrowers with DTI less than 15 to be granted of 60 month term loans since above that there is very high default with overall defaul percentage of 25% for this term.
- Grade E,F,G categories default the most in High value loans and dti above 15 has very high default ratio hence it is recommended to grant only to dti less than 15 and whose income is verified.

## Technologies Used
- python
- pandas
- numpy
- matplotlib
- seaborn
- plotly


## Acknowledgements
Give credit here.
- This project was inspired by Lending club case study
- References 

## Contact
Created by [@jayadeepanraj] - feel free to contact me!
