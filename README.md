# Project Name
> Lending Case study :
    Lending Club is an online loan facilitator providing personal loans, business loans, and financing of medical policy.
    Borrowers can easily avail  loans quickly through its online portal at a lesser interest rate.
    Lending Club seeks to gain insight into the drivers of loan default, namely the driver variables, which are potent indicators of default. 
    This information can be used by the company to inform its portfolio management and risk assessment.


With this case study As a Lending Club data analyst, I analyze the dataset containing information about past loan applications using EDA to understand how consumer attributes and loan attributes influence the trend of default.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendation](#Recommendation)
* [Acknowledgements](#acknowledgements)


## General Information
- Lending Club seeks to gain insight into the drivers of loan default, namely the driver variables, which are potent indicators of default. 
   This information can be used by the company to inform its portfolio management and risk assessment.
- With this case study As a Lending Club data analyst, I analyze the dataset containing information about past loan applications using EDA to    understand how consumer attributes and loan attributes influence the trend of default.
- We are given with loan data  which contains  information for all loans issued through the time period 2007 t0 2011. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- OverAll Loan data has 83%(32950 loans) fully paid, 14%(5627 loans) Charged off, 3%(1140) Current loan
- Most of the Loans which was charged off has DTI  between 6 to 24,any variable that increases the DTI higher than 16.5% should be considered as business Risk.
- Most of the Loans which was charged off has annual_income between 0 to 300K and loan amount between 0 to 40k and interest rate between 5 to 25 %
- On an Average Charged Off loans has annual_income = 62427.298034 ,dti_ratio = 14.000624 interest_rate = 13.820432 ,loan_amount	12104.385108
- Maximum number of loans are for debt consolidation, followed by credit card 
- Lower grades have a higher incidence of defaults on loans. This shows that the grading system is working.
- Lending Club charges higher interest rates as the grade of a loan becomes worse.
- Percentage of Defaults increases monotonically with higher interest rates. At rates of 19% and above, more than 33% of loans are Charged Off. 
- More than a quarter of loans are taken for the purpose of running a small business see defaults.
- Percentage of default rises with dti ratio. As the DTI ratio rises above 14, the loans become risky.
- Higher interest rates should be charged for higher dti, but we see a spread across all values

## Recommendation
Stop : approving loans where the amount/income is higher than 30%

Reduce : the number of approvals where the purpose is a small business

Stop : approving high-value loans when the revolving line utilization rate is greater than 75%

Stop : approving loans to people with prior bad records. Or at least stop approving high-value loans

Start : charging higher interest rates for loans with DTI greater than 14



## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.23.5
- matplotlib - version 3.7.0
- seaborn - version 0.12.2



## Acknowledgements
- This project has helped to  develop a basic understanding of risk analytics in banking and financial services and understand how data is used  to minimise the risk of losing money while lending to customers.
- Geeks for Geeks and official documentaion of python libraries has helped a lot to understand the charts and best utilization of it.
- Special Thanks to Sandeep Roy who has equally contributed to this project .


## Contact
Created by sumanji.aec@gmail.com  - feel free to contact me!
