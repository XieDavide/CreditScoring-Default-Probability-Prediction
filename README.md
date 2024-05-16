# CreditScoring-Default-Probability-Prediction 🏦
co-authors: HARSHIT KHANDELWAL, NICOLÒ CHEN, JORDI MURADYAN 
## Introduction

Banks use credit scoring algorithms to estimate the probability of default when deciding whether a loan should be granted. <br/>
In the project, the task will be to build a credit scoring algorithm predicting the probability that somebody will experience financial distress in the next two years. The goal of this project is to build a model that loan providers can use to help borrowers make the best financial decisions. <br/>


## Datasets <br/>
-- _train.csv_: training data that you can use to train your algorithms;<br/>
-- _test.csv_: test data for which you have to make predictions;<br/>
-- _submission.csv_: an example of the structure of the final csv file that you’ll have to upload as part of your final submission.<br/>

## Description
• **SeriousDlqin2yrs**: Person experienced 90 days past due delinquency or worse (Y/N) (this is your target!)<br/>
• **RevolvingUtilizationOfUnsecuredLines**: Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits (percentage)<br/>
• **Age**: Age of borrower in years (integer)<br/>
• **NumberOfTime3059DaysPastDueNotWorse**: Number of times borrower has been 30-59 days<br/>
past due but no worse in the last 2 years (integer)<br/>
• **DebtRatio Monthly**: debt payments, alimony, living costs divided by monthly gross income
(percentage)<br/>
• **MonthlyIncome**: Monthly income (real)<br/>
• **NumberOfOpenCreditLinesAndLoans**: Number of open loans (installment like car loan or
mortgage) and lines of credit (e.g. credit cards) (integer)<br/>
• **NumberOfTimes90DaysLate**: Number of times borrower has been 90 days or more past due
(integer)<br/>
• **NumberRealEstateLoansOrLines**: Number of mortgage and real estate loans including home
equity lines of credit (integer)<br/>
• **NumberOfTime60-89DaysPastDueNotWorse**: Number of times borrower has been 60-89
days past due but no worse in the last 2 years. integer<br/>
• **NumberOfDependents**: Number of dependents in family excluding themselves (spouse,
children etc.) (integer)<br/>

## Metric
For each test input you will have to predict the probability of financial distress in the next two years.<br/>
The metric with which we will evaluate your predictions is AUC 

# Notes🙋🏻‍♂️
-- Follow the Jupyter Notebook called [project_code](https://github.com/XieDavide/CreditScoring-Default-Probability-Prediction/blob/main/project_code.ipynb) (and pip install certain libraries if needed) <br/>
-- The final production consists of a 5-page [report](https://github.com/XieDavide/CreditScoring-Default-Probability-Prediction/blob/main/ML_report.pdf) and analysis of the problem, the approach to it, and the model and its performance. <br/>
