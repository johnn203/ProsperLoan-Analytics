[README.md](https://github.com/johnn203/ProsperLoan-Analytics/files/9695432/README.md)
# ProsperLoan-Analytics
## Exploration of Prosper Loan Data
## by Akoh John Ojoarome

## Introduction

>An Exploratory analysis into Prosper loan data for the purpose of uncovering insights and communicating findings through data visualisation.

>Prosper loan isa peer-to-peer lending company based in San Francisco, Carlifornia, which provides a platform for borrowers and lenders to buy and invest in loan financing. The purpose of this analysis is to investigate how explanatory factors such as Credit worthiness, LoanOriginalAmounts and LoanStatuses influence and interact with interest rates.

## Utilities

>Conda 4.8
>Python 3
>Jupyter Notebook
>Pandas
>Numpy
>Matplotlib
>Seaborn

## Dataset
Prosperloandata.csv
>Dataset was Provided for analysis by Udacity as course completion requirement in its Data Analysis Nanodegree.
>The Dataset is a csv file containing 81 features of113937 listed loans, some of which were investigated in this project e.g BorrowerAPR, CreditScoreRange, LoanStatus, LoanOriginalAmount, EmploymentStatus e.t.c

Data dictionay
>The variables explored in this project were briefly described in a google spreadsheet containing all features releated to the Prosper loans. This file was provided by Udacity.

Cleanloan.csv
>This file was created after wrangling exercises, as a point of reference/backup.

## Data Wrangling

>Comprehensive  Overview of Dataset
>Interested variables were selected which were 19 in total.
>Assessment was conducted and several quality and structural issues were identified.
>The data cleaning process involved addressing null values, ordering ordinal categorical variables, Changing datatypes and remapping values using the Define-Code-Test framework.
> A copy of the cleaned dataset was made.

## Summary of Findings

>We investigated the interactions of LoanStatus, CreditScoreRange, LoanOriginalAmounts with BorrowerAPR as a indicator of Loan favorbility, using a combination of numerical and qualitatie analysis. BorrowerAPR being our main variable had a majority of loans listed at 35%. we find that most borrowers preferred a loan Term of 36 months, 79% of Borrowers were Employed, with 62% of Loans requested for Debt Consolidation.

>With Focus on BorrowerAPR, we observed its positive correlation with EstimatedLoss, DebtToIncomeRatio, as well as its negative correlation with LoanOriginalAmount, ProsperScore, CreditScoreRange, IncomeRange and ProsperRating. In addition, we observed that EstimatedLosses were highest at Loan Term of 12 months.

>From our Bivarite exploration of BorrowerAPR vs CreditScoreRange, we observe a negative correlation as stated above, up untill the Highest CreditScoreRange were we begin to notice a rise in average BorrowerAPR, which is in contrast to the prior trend of average BorrowerAPR declining, following an improvement in CreditScoreRange. Upon further exploration, we observed that at CreditScoreRange (880-899), the average loan amounts of Completed Loans incresed warranting lower BorrowerAPR, but the average LoanOriginalAmounts of Current Loans declined greatly, which might warrant higher BorrowerAPR.


## Key Insights for Presentation

>In this presenttion, i seek to visually communicate the unusual relationship between CreditScoreRange and BorrowerAPR as seen in the Bivariate violin plot. I look into what factors might be responsible for the avergae BorrowerPR of the Highest CreditScoreRange being Higher than the previous range, despite the negative correlation largely observed between BorrowerAPR and CreditScoreRange.

>I will begin by introducing most of the relevant features in our exploration, their distributions and correlations.
