# LendingClub Case Study

## Problem Statement


• The purpose of this case study about a consumer finance company which specializes in
lending loans to urban customers.
• The company wants to understand the risk associated to approving loan to customers.
• Not approving loan to customers who are likely to repay will result in loss to the
business.
• Approving loan to customers who are not likely to pay will result in financial loss to the
company.
• Objective is to identify the driving factors behind loan default using the given dataset.

## Given dataset
loan.csv file

## About the dataset

• The given dataset contains data from period of 2007 to 2011 with records of approved
customers and their data of the loan status along with other variables.
• The target variable is the loan_status using which we can identify if a customer has repaid
the loan or has defaulted.
• Categorical Variables
• Ordered Categorical Variables: emp_length, income_bucket, interest_bucket, issued_quarter, term
• Unordered Categorical Variables: addr_state, purpose, grade, verification_status, home_ownership
• Continuous Variables
• int_rate, annual_income, dti, open_acc, revol_bal, revol_util, total_acc, total_payment, total_due,
loan_amount

## Technologies used
The following python libraries were used
• Pandas
• Matplotlib
• Seaborn

## Conclusions from the dataset

From the analysis the following can be concluded:
• The given dataset contains a larger number of Fully Paid customers compared to Charged Off customers [Slide 8].
• More number of loan applicants are from California state. More number of defaulters are from California state
[Slide 12].
• People who have been issued loan in the 4th quarter of the year have defaulted more [Slide 9].
• People who have taken loan for debt consolidation have defaulted more compared to other category of loan
application purpose [Slide 10].
• People who have VH interest tend to default more. Contrary to it, people who have VL interest fully pay off their
loan [Slide 11].
• People in Rented home and home on Mortgage, have a larger number of defaulters [Slide 13].
• People in VL incomer bucket tend to have more defaulters. People in VH income bucket have more number of
fully paid [Slide 15].
• People with 10+ years of employment length default more compared to other levels of experience [Slide 16].

• Customers with loan purpose as debt_consolidation, and 4th quarter of the years have defaulted more
[Slide 17].
• Customers who apply for loan for debt_consolidation defaulted have higher median debt to income ratio
(dti) [slide 18].
• Customers who have defaulted have higher revol_util median compared to fully paid customers. A
higher revol_util means they already have a higher credit balance to pay off [Slide 19].
• Customers who have defaulted on loan have higher median int_rate slide[20].
• Customers who have defaulted have higher number of inquires in the last 6 months. The median and 75th
percentile value of inq_last_6mths variable is higher for those who have defaulted on loans [Slide 21].