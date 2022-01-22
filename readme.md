# Loan Dataset Exploration 
## by Marwan Mohamed Mohamed Zidan


## Dataset

> The data set consists of 110811 loan records and 11 loan attributes , those attributes include the amount of loan , interest rate , loan status , the duration of loan and etc...


## Summary of Findings

> loan original amount has postive cooleration with monthly payment , term and inverstors

> borrwer rate has negative cooleration with monthly payment, inverstors , but it has postive cooleration with term

> loan original amount and borrower rate has negative cooleration

> the lower the income the more likely the loan will not be completed and fail

> bad loans have higher borrower rates than normal loans

> the borrower with no home has more borrower rate

> employmed people have borrower lower rate than not employed

> loan type varies according to the loan amount and borrower rate , as the bad loans are more likely to happen in higher borrower rates and lower loan amounts 

> loan amount has a postive cooleration with investors as the number of ivnestors increase the loan amount also increase

> the monthly payment has a postive relation with investors and loan amount as the monthly payment increases when the number of investors and loan amount increase


## Key Insights for Presentation

> At first we choose the columns and variables of interests , then we cleaned our data for exploration by removing nan values and duplicates , then we started by plotting our columns and 
adjusting some graphs to log scale such as investors and monthly payment , then we focused more into the main features such as loan status which we made some work on to divide it into
2 types of loan (normal and failure) and then plotting it with the income range , then compared other features with the 2 numeric main features , then at the end we plotted the 3 main
features together to interpert their relation with each other.