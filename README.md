# MIE1624HW1---Data-Science-Analytics-on-Stack-Overflow-Survey

This project analyzes the 2024 Stack Overflow Developer Survey to study salary differences across job modes and education levels using Python.

## Methods
- Exploratory Data Analysis (EDA): demographics, salary, job satisfaction
- Hypothesis Testing:
  - Two-sample t-test (manual + Welch’s)
  - ANOVA for education levels
- Bootstrap (10,000 replications) for robust estimation
- Assumption checks: Shapiro-Wilk (Normality), Levene (Equal variance)

## Results
- Remote workers earn on average ~$39,664 more than in-person workers (p ≈ 0)
- Salary differences by education are significant:
  - Bachelor > Master (+$2,317)
  - Master < Professional (–$17,536)
  - Bachelor < Professional (–$15,219)
- Bootstrap validated robustness of findings

## Skills Demonstrated
- Data analysis and visualization in Python
- Statistical inference: t-tests, ANOVA, bootstrapping
- Critical evaluation of model assumptions
