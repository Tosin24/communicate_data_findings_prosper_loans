# Prosper Loan Dataset Exploration
## by Oluwatosin Obisan


## Dataset

This project explores the data set from Prosper Loans. Prosper Funding LLC operates Prosper.com, a website where individuals can request to borrow money. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower APR, current loan status, borrower income, and many others. The data set can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) while the dictionary that explains the variables in the data set can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Summary of Findings

The purpose for exploring this data set was to investigate the factors that affect the annual percentage rate (APR) of the borrowers. From investigating the original loan amount column and the borrowers APR columns, I found that the APR has a wide range for each loan amount. However, the two variables are negatively correlated, i.e., the annual percentage rate reduces as the loan amount increases. A follow up investigation into the determinant factor of the loan amount reveals that the stated monthly income of the borrowers is a contributing factor to the original loan amount given to the borrowers, as the two variables are positively correlated. I concluded that the monthly income of the borrowers contributed to the loan amount they received which in turn decides to a certain degree the APR.

A further investigation into the prosper rating column as a factor that affects the annual percentage rate (APR) of the borrowers, reveals that the rating ascribed to the borrowers is certainly a factor. The ratings of the borrowers were ranked from AA to HR, with AA being the lowest loan risk, and the HR being the highest loan risk. The borrowers with AA rating were given loans with the lowest APR, while those rated HR got loans with the highest APR.  I also investigated the homeownership column as a factor, and the result reveals that homeowners received lower APR than non-homeowners.

Asides the main variables of interest, other variables I investigated was the pattern of the APR over the years, I found that the APR was at an all time low in 2014, while the peak was in 2011. Exploring the term variable reveals that majority of the borrowers were given a loan term of 36 months, irrespective of their rating or employment status, while a sizable number of them were give a loan term of 60, borrowers with a loan term of 12 months were in the minority.

## Key Insights for Presentation

Since the focus of the project is to investigate the factors that affect the annual percentage rate (APR) of the borrowers, I restricted my presentation to those factors. The original loan amount is a factor that contributes to the APR. Borrowers that received a large amount in loans got lower APR, the wide range in the APR for the loan amount depends on other factors such as if the borrowers own a home or not, another contributing factor is the ratings of the borrowers.
