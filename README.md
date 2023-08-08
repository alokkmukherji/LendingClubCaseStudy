# Lending Club Case Study 
A lending company facilitates loans for different pupose like personal loans, business loans, medical procedures. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss / credit loss. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. The number of defaulters can be reduced by identifying risky loan applicants at the time of loan approval. The goal of this project is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default so that this information can be utilised for risk assessment during loan approval. 
 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The main objective of this analysis was to find some drivers for the case of loan default based on the input dataset
- Steps followed for this analysis :  Reading input data -> data cleaning -> univariate analysis -> segmented univariate analysis -> bivariate correlation analysis -> conclusion 
- Input dataset used for this analysis had 39717 rows and 111 columns
- The data cleaning step included
  1. dropping cloumns having no value
  2. checking for duplicate data
  3. reformatting column value (by changing data type,removing unwanted patterns etc.) suitabe for data analysis
  4. removing outliers
  5. creating separate month & year column from issue_d
  6. removing columns having same value
- The no. of rows and columns reduced to 37398 and 21 respectively, This reduced dataset was used for further analysis
   
 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-  After univariate, segmented univariate and bivariate analysis, the list of drivers for loan default mentioned below were identified: 
  1. Interest rate - Higher the interest rate, the chance of loan default is more
  2. Anual income  - Lower the income, the chance of loan default is more
  3. Loan grade    - Chance of loan default is more for loan grade G
  4. Loan sub grade - Chance of loan default is more for loan sub grade F5
  5. Loan term      - Higher chance of loan default for loan term 60
  6. Purpose of loan - Higher chance of loan default if loan is taken for small business
  7. Loan amount      - Higher chance of loan default if loan amount is high
  8. No. of installment - Higher chance of loan default if no. of installment is more 
  9. The length of employment - Higher chance of loan default is for fresher

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.0 (Python lib used - numpy, pandas, seaborn, matplotlib)
- Jupyter notebook
- Exploratory Data Anlysis (EDA) Concept

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Upgrad 


## Contact
Created by alokkmukherji@gmail.com / akshaykachroo2050@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
