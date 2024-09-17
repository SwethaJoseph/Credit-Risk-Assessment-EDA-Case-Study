# Credit-Risk-Assessment-EDA-Case-Study
## Overview
This project focuses on Credit Risk Assessment by performing an Exploratory Data Analysis (EDA) using Python. The goal is to identify patterns and key factors that contribute to loan defaults, thereby supporting more informed lending decisions and improving the overall quality of the loan portfolio. The analysis is conducted using two datasets: one containing current loan application data and another detailing previous loan applications.

## Datasets
* application_data.csv: This dataset includes detailed information on current loan applications, such as client demographics, income, loan amount, and other financial indicators.
Rows: 307,511
Columns: 122

* previous_application.csv: This dataset contains records of previous loan applications made by clients, providing insights into their borrowing history and past interactions with the lending institution.
Rows: 1,670,214
Columns: 37

## Key Objectives
* Identify Key Risk Factors: Determine factors that indicate a higher likelihood of loan defaults.
* Improve Lending Strategies: Use insights from the analysis to optimize loan approval processes and reduce financial losses.
* Enhance Risk Assessment: Develop improved models for assessing credit risk, focusing on high-risk clients.

## Data Analysis Workflow
1. Data Cleaning & Preparation
* Handling Missing Values: Columns with more than 50% missing data were dropped, and imputation techniques were applied to other missing values.
* Removing Unnecessary Columns: Irrelevant columns were removed to streamline the analysis.
* Outlier Detection: Boxplots and the IQR method were used to identify and address outliers in key financial variables.
  
2. Exploratory Data Analysis (EDA)
* Descriptive Statistics: Basic statistical summaries and visualizations to understand data distribution.
* Risk Analysis:
Numerical Features: Analyzed distributions and potential risk factors such as loan amounts and income levels.
Categorical Features: Examined the impact of variables like loan type, gender, and income source on default rates.
* Correlation Analysis: A heatmap was used to explore correlations between variables and their relationship with loan default risk.
* Pair Plot Analysis: Investigated relationships between financial variables and their impact on loan defaults.
  
3. Merged Data Analysis
* Combining Datasets: Merged current and previous loan application data for a comprehensive analysis.
* Approval Trends: Analyzed trends in loan approval amounts and their evolution over time.
* Client History: Assessed the impact of client history and loan types on default risk.

## Key Findings
* Default Distribution: 91.9% of the dataset consists of non-defaulters, while 8.1% are defaulters.
* Age and Default Risk: Younger age groups (20-39 years) have a higher proportion of defaults, indicating that age may influence repayment behavior.
* Income and Credit Risk: High-income outliers exist, but most clients have lower incomes, suggesting income alone may not be a strong predictor of default.
* Loan Type and Gender: Cash loans dominate, with varying default rates depending on client history. Gender does not appear to be a significant differentiator in repayment difficulties.
* Correlation Insights: Higher external credit scores and older age are associated with a lower likelihood of loan default, while shorter employment duration slightly increases default risk.
  
## Tools & Technologies
* Python: Used for data analysis with libraries such as NumPy, Pandas, Matplotlib, and Seaborn.
* Jupyter Notebook: Employed for running the Python code and performing EDA.
* Visual Studio Code: Used as the development environment for the project.

## Conclusion & Recommendations
* Focus on high-risk clients, particularly younger individuals and those with lower credit scores, by enhancing scoring models with additional variables like occupation and contract types.
* Prioritize loan approval for clients with longer employment histories, as this correlates with lower default risk.
* Diversify the loan portfolio by focusing on products with lower default rates.
* Consider using enhanced risk assessment models to improve the prediction of defaults.
  
## How to Use
* Open the Jupyter Notebooks:
Open PYTHON EDA PROJECT- ANALYSIS PART1.ipynb and PYTHON EDA PROJECT- ANALYSIS PART2.ipynb in Jupyter Notebook or Visual Studio Code to explore the data analysis process.
* Run the Analysis:
Execute the cells in the Jupyter Notebooks to perform the EDA and view the results.

## Contact
For any questions or suggestions, please reach out to  [LinkedIn | Swetha Kizhavana Joseph](https://www.linkedin.com/in/swetha-kizhavana-joseph-04b68721b/)
