# Project Name
> This project analyzes Consumer Finance Company Loan Data to identify drivers of loan default

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project analyzes Consumer Finance Company Loan Data
- This is case study for EDA module of upGrad and IIITB Machine Learning & AI Program - February 2024 batch
- The intent of this analysis is to help the company understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of  default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- The dataset used for analysis is in this github repo with name loan.csv

## Conclusions
- To mitigate default risk, aim to keep the interest rate below 12%.
- The company should consider diversifying loan purposes by exploring opportunities to allocate a greater portion of loans towards categories like car purchases, credit card payments, home improvements, weddings, and major purchases. These categories typically exhibit lower default rates. Simultaneously, efforts should be made to reduce the overall proportion of loans designated for debt consolidation.
- The following borrowers are at a higher risk of default
  - Those with history of 30+ days past due incidences (delinquencies), derogatory public records, or public bankruptcy records.
  - Having utilization rate above 30%
  - Having DTI above 8
  - Having more than 1 loan inquiry in last 6 months.
  - Having a record of Recovery fees paid
- For future loans extended to borrowers satisfying above conditions, it is advisable to mitigate risk by offering smaller loan amounts and/or higher interest rates.

## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.2.1
- seaborn - version 0.13.2
- matplotlib - version 3.8.3

## Acknowledgements
- Thnaks to beautiful explanation by Gramaner CEO, Anand S in the content put together by upgrad and IIITB

## Contact
Created by @sivavaddadi - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
