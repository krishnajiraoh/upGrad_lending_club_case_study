# Lending Club Case Study
The project aims to aims to analyse the past data of a lending company, to draw meaningful insights which would help to manage its portfolio better and thereby improving its overall revenue.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendations](#recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

 The project is for a consumer finance company which specialises in lending various types of loans to urban customers. In this project, will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

Business Problem:
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Dataset:
- The given data contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Conclusions
1. “term” is a strong driver variable of default
    - At least 1 out of 4 loans (25%) in “60 months” term end up defaulting
2. “purpose” is a strong driver variable of default
    - Ex: at least 1 out of 4 loans (>25%) in “small business” end up defaulting
3. “grade” is a strong driver variable of default
    - Ex: More than 30% of loans in grade G & F end up defaulting
4. “sub_grade” is a strong variable of default
    - More than 40% of loans in sub_grade “F5” & “G5” end up defaulting
5. “addr_state” is a strong variable of default
    - Ex: more than 20% of loans in addr_state “NV” & “AK” end up defaulting
6. Fully paid loans have much higher emi_burden values than that of defaults 
    - Defined as the ratio of “annual_inc” to “installment”
    - The medians of the calculated emi_burden are ”173” & “205” for “Charged Off & “Fully Paid” respectively.
7. Defaulters have significantly higher “loan_amnt” for “purpose” – “small_business”, “credit_card”, “renewable_energy” categories

## Technologies Used
- pandas - version 1.5.0
- numpy - version 1.21.0
- seaborn - version 0.12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by @krishnajiraoh - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
