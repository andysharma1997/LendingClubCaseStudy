# Lending Club Case Study

## Overview
> This case study focuses on performing an Exploratory Data Analysis (EDA) on Lending Club's loan data to extract meaningful insights regarding loan characteristics and borrower behavior. The goal is to identify patterns and trends that can inform future lending strategies and understand the driving factors behind loan defaults. By analyzing these factors, the company can better assess portfolio risk and optimize lending decisions.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information <a class="anchor" id = general-information></a>
- **Project Background:** Lending Club, a peer-to-peer lending company, seeks to enhance its understanding of borrower behavior and loan performance. This analysis aims to identify the key factors influencing loan defaults and successful repayments.
- **Business Problem:** The primary objective is to uncover the variables that strongly indicate the likelihood of loan default. By understanding these factors, Lending Club can improve its risk assessment processes, minimize defaults, and maintain a healthier loan portfolio.
- **Dataset Used:** The dataset includes detailed information on loans issued by Lending Club, including borrower demographics, loan characteristics, repayment status, and more.

## Conclusions
1. **Loan Performance:** The number of fully paid loans significantly outnumbers defaulted loans, with most loans being of high grade (A and B), indicating that Lending Club primarily caters to lower-risk borrowers.
2. **Loan Term and Risk:** Loans with a 60-month term have a higher likelihood of default compared to 36-month loans, which are more commonly associated with higher grades and lower default rates.
3. **Borrower Characteristics:** Borrowers with annual incomes below $50,000 are more likely to default, while those with higher incomes tend to take out larger loans, showing a moderate positive correlation (r = 0.41) between loan amount and income.
4. **Interest Rate Dynamics:** The interest rate correlates moderately with the loan term (r = 0.44), with longer terms associated with higher interest rates, indicating a potential risk factor that Lending Club should manage carefully.

## Technologies Used
- Python==3.10.12
- Pandas==2.2.2
- NumPy==2.0.1
- Matplotlib==3.9.1
- Seaborn==0.13.2
- plotly==5.23.0
- Jupyterlab==4.2.1

## Acknowledgements
- This project was inspired by the need to better understand borrower behavior and loan performance at Lending Club.
- Data and analysis techniques were based on common practices in data science.
- Special thanks to the open-source community for providing the tools and resources used in this project.

## Contact
Created by [Shubham Sharma](https://www.linkedin.com/in/shubham-sharma-andy) - feel free to contact me!