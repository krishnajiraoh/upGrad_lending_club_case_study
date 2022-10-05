# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendations](#recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. “term” is a strong driver variable of default
    - At least 1 out of 4 loans (25%) in “60 months” term end up defaulting
2. “purpose” is a strong driver variable of default
    - Ex: at least 1 out of 4 loans (>25%) in “small business” end up defaulting
3. “grade” is a strong driver variable of default
    - Ex: More than 30% of loans in grade G & F end up defaulting
4. “sub_grade” is a strong variable of default
    - More than 40% of loans in sub_grade “F5” & “G5” end up defaulting
5. Fully paid loans have much higher emi_burden values than that of defaults 
    - The medians of the calculated emi_burden are ”173” & “205” for “Charged Off & “Fully Paid” respectively.

## Recommendations
1. For the state “WY”,  and a threshold of 10%,
    - Acceptable “loan_amnt” = 10375 + 10% of 10375
2. The "int_rate" for the state "WY" is recommeded to be not more than "12.61%"

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
