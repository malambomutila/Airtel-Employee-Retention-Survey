# Employee Retention Survey at Airtel Zambia 2023
This analysis reproduces the results obtained by Mwila (2023) in a study on employee turnover and retention in the telecommunications services sector in Zambia. The data used was from an online survey conducted by Mwila (2023) involving employees at Airtel Zambia. This analysis focuses on age and employee retention. 

### Aim
To use Python to reproduce survey analysis results obtained in SPSS.

### Guiding Questions
To reproduce the results obtained by the Mwila (2023). The goal of this data analysis was to answer the following questions:

- What factors contribute to high employee turnover at Airtel Networks Zambia?
- Do policies impact the reduction of staff turnover and improve performance at Airtel Networks?
- What are the differences in turnover rates among various age groups of employees at Airtel Networks?

### Methodology

1. Data Cleaning
2. Reliability Test
3. Descriptive Statistics

### Data Cleaning

Firstly, the raw data was read into a Pandas dataframe, containing columns named Timestamp and Score, which were subsequently dropped from the dataset. Following this, uniform naming conventions were applied to the columns. Next, the data was split into quantitative and qualitative subsets. 

The last four qualitative questions were dropped to isolate the quantitative data. Subsequently, the columns were renamed to ensure consistency and clarity. Value labels where assigned and a glossary of variables was then created to document the variable names alongside their corresponding original questions or descriptions.

Further cleaning involved dropping rows with missing values and replacing specific responses to standardise the data. <br>

Glossary obtained by Mwila (2023) in SPSS<br>
![1_spss](https://github.com/malambomutila/Airtel-Employee-Retention-Survey/assets/77410865/c73125ac-b919-4c0d-ba65-f98e590ae49f)

Glossary obtained using Python<br>
![1_python](https://github.com/malambomutila/Airtel-Employee-Retention-Survey/assets/77410865/cf2a5d84-1782-4289-9057-5ce89f2feeaf)

### Reliability Test
Cronbach's Alpha was used to test the internal consistency and reliability of the questionnaire and the quantitative results.<br>
The Cronbach Alpha values are in the range 0 – 1.0. The values between 0.70 to 0.80 are in an acceptable range, and the values greater than 0.80 are considered the most desirable. 

The questionnaire scored 0.764 both in SPSS and with Python, meaning it had acceptable internal consistency and reliable results. 

SPSS Cronbach's Alpha Test<br>
![2_spss](https://github.com/malambomutila/Airtel-Employee-Retention-Survey/assets/77410865/7c6a3ad6-1032-4e83-8401-40fb6ecb9929)

Cronbach's Alpha Test with Python<br>
![2_Python](https://github.com/malambomutila/Airtel-Employee-Retention-Survey/assets/77410865/fd9cfaf8-36f7-419a-b638-610ba29cc47f)

### Descriptive Statistics
Key statistics generated included grouping respondents by gender and also by age, correlation tests, crosstabulation and Chi-square tests.

### Conclusion
The results of the survey analysis using Python were identical to the results obtained by Mwila (2023) using SPSS.

Key insights were as follows:
1. Factors contributing to high employee turnover at Airtel Networks Zambia
- Insufficient remuneration, according to 78% of workers, is a major factor in job turnover. Of the employees, 22% were not sure or did not know if low pay has a major role in increasing employee turnover.
- When asked what would persuade them to stay longer, 44% of workers stated that a raise in pay and 49% that a better work-life balance would persuade them to stay longer.

2. Age and Employee Turnover
- Age and years worked were found to have a significant association.
- Age and job satisfaction were also found to have a significant association.
- Age was found to be significantly linked to how employees feel about advancement opportunities within a company.
