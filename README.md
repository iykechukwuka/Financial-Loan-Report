# Loan Default Analysis Project

## Project Overview
This project analyzes a dataset containing loan applications, including borrower information, loan details, and repayment status. The goal is to identify patterns that contribute to loan defaults and suggest recommendations to improve lending practices. By exploring features such as employment, income, loan amount, and payment history, this project aims to highlight factors associated with successful repayments and loan defaults.

## Dataset Description
The dataset consists of the following columns:

- **id**: Unique loan ID.
- **address_state**: State of residence of the borrower.
- **application_type**: Whether the loan is individual or joint.
- **emp_length**: Length of employment in years.
- **emp_title**: Job title of the borrower.
- **grade**: Loan grade assigned by the lender.
- **home_ownership**: Ownership status of the borrower's residence (Rent, Own, Mortgage).
- **issue_date**: Date when the loan was issued.
- **last_credit_pull_date**: Date when the borrower's credit was last checked.
- **last_payment_date**: Date of the borrower's last payment.
- **loan_status**: Current status of the loan (Fully Paid, Charged Off, etc.).
- **member_id**: Member ID of the borrower.
- **purpose**: Purpose of the loan (e.g., car, debt consolidation).
- **sub_grade**: Subgrade within the main grade.
- **term**: Loan term (36 or 60 months).
- **verification_status**: Whether the borrower's income was verified.
- **annual_inc**: Annual income of the borrower.
- **dti**: Debt-to-income ratio of the borrower.
- **installment**: Monthly loan installment amount.
- **int_rate**: Interest rate applied to the loan.
- **loan_amount**: The total loan amount issued.
- **total_acc**: Number of credit accounts held by the borrower.
- **total_payment**: Total amount paid towards the loan.

## Analysis Goals
- **Exploratory Data Analysis (EDA)**: Examine the distribution of loan grades, employment lengths, and repayment statuses.
- **Correlation Analysis**: Identify relationships between key variables (e.g., income, DTI, loan amount, interest rate) and loan defaults.
- **Default Prediction Model**: Build a predictive model to estimate the likelihood of a loan default based on borrower characteristics.

## Insights and Recommendations
1. **Risk Profiles**: Higher default rates are observed in certain loan grades (e.g., C and E), suggesting a need for stricter credit checks for these categories.
2. **Income and DTI**: Loans with higher DTIs have a higher probability of default, suggesting that DTI should play a more prominent role in loan approval decisions.
3. **Loan Terms and Default**: Longer-term loans (60 months) are riskier for certain borrowers. Adjusting loan terms based on risk profiles may reduce defaults.
4. **Interest Rates**: Higher interest rates correlate with higher default rates. Offering lower interest rates for high-risk customers might improve repayment outcomes.
