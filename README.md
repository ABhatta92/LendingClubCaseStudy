# Lending Club EDA
> Exploratory Data Analysis for Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Exploratory Data Analysis to determine the factors which conttribute to defaults on loans offered on Lending Club using the dataset provided in the repo at /data/loan.csv


## Technologies Used
- Python 3.11.0
- numpy 1.24.2
- pandas 1.5.2
- matplotlib 3.6.2
- seaborn 0.12.2
- MS Excel


## Conclusions
### Numerical Columns
- Those who default tend to get loans at a higher interest rate as compared to those that do not
- Those who have fully paid off their loans tend to have a higher income that those who default on their loans
- The DTI is higher for those who default as compared to those who do not
- Revol_util is higher for defaulters, indicating that they tend to use up more of their available lines of credit as compared to those who have not defaulted
### Categorical Columns
- The percentage of defaulters with one public record bankruptcy is twice that of non-defaulters with one public record bankruptcy
- There are no defaulters with more than 2 derogatory public records, however non-defaulters have more
- As far as grade is concerned, very few defaulted loans are grade A (of those, the majority are A4/A5). However, among non-defaulters, more than a quarter of the loans are grade A.