# Exploring Prosper Loan Data
#### by Egwuda Ojonugwa Everest - October 2022

## Overview
The aim of this project is to analyze data from Prosper Marketplace, a company that majors in providing loans at low interest rates to borrowers. The dataset for this project was provided by Udacity and contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income etc.

## Dataset
The dataset can be found on [Udacity](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000), and a detailed explanation of all its features can be obtained from [Here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

## Preliminary Wrangling
Of the 81 features in the dataset, 15 were selected for exploration, During Data cleaning, duplicate records were removed, data types not matching the variables were converted, and null records for the key variables were dropped. State longitude and latitude information was gathered from data uploaded by GitHub user, [Rashida048](https://raw.githubusercontent.com/rashida048/Exploratory-data-Analysis-in-R/main/statelatlong.csv), to aid the visualization of loan patterns across states. At the end of the wrangling process, 83,982 loan records and 18 variables remained for analysis.

## Summary of Findings
Most of the borrowers took loans to refinance previous debt and not for business or asset purchase as should be the case with loans. Asides business purposes, borrowers depended on huge loans to finance weddings, child adoptions, boat acquisitions, and the purchase of engagement rings.

Employed people take out loans more than unemployed which is expected as there is a source of income to pay back also ProsperRating affects the amount of loan a borrower can take with a better ProsperRating meaning higher loan amount.

BorrowerState ie State ie state where the borrower was at the time of the listing plays a role in the amount requested by the borrower with more people from major states and cities.

## Key Insights for Presentation
2 bar plot explaining the reason why borrowers take loans through prosper, with the reasons one bar plot and the average amount they borrow on another.
Borrowers demograhy ie Location and states, was looked at to get a proper represention of the borrowers.Also influence of prosper rating on loan interest rate was explained with a plot with Prosper rating the key variable tocompare with borrower APR.
