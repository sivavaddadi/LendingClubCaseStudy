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
- The company should contemplate diversifying loan purposes by decreasing the overall percentage of loans earmarked for debt consolidation. Instead, it should increase loan allocations toward categories such as car purchases, credit card payments, home improvements, weddings, and major purchases. These categories were found to have lower default rates, thereby are good options to mitigate default risk.
- Borrowers falling into the following categories are at a heightened risk of default:
  - Individuals with a history of 30+ days past due incidences (delinquencies), derogatory public records, or public bankruptcy records.
  - Those with a loan revolving utilization rate exceeding 30%.
  - Borrowers with a debt-to-income ratio (DTI) surpassing 8.
  - Individuals who have made more than one loan inquiry in the last 6 months.
  - Borrowers with a record of paying recovery fees.
- For future loans extended to borrowers meeting the aforementioned conditions, it is advisable to mitigate loan default risk by considering strategies such as offering smaller loan amounts and/or higher interest rates. These measures can help offset the increased default risk associated with these borrower profiles.

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
