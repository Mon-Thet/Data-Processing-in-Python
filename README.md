# Data Processing in Python: Understanding Household Income & Spending

## Project Overview

This project analyzes household income and expenditure patterns to understand how different economic and demographic factors influence spending behaviors. Using data processing, exploratory data analysis (EDA), and machine learning models, we predict household expenditures based on key variables such as income, education, household size, and savings behavior.

# Project Setup

To replicate this analysis, follow these steps:

### Install Required Libraries

Ensure that you have the necessary Python libraries installed by running:

`pip install -r requirements.txt`

### Execute the Script

Place the dataset in the appropriate directory and execute the script with:

`python income_vs_expenditure_analysis.py`

The script will generate **visualizations, statistical summaries, and model predictions.**


## Hypothesis

>Household expenditure patterns are influenced not only by income levels but also by educational attainment.Higher education levels contribute to better financial decision-making, resulting in increased savings and reduced non-essential spending.

Theory Basis:This study aligns with Human Capital Theory, which suggests that education increases earning potential and promotes better financial stability.

## Dataset Overview

The dataset contains detailed records on:

- **Income Levels** – Categorized into **Very Low, Low, Middle, Upper Middle, and High** based on quantiles.

- **Total Expenses** – Summarizing household expenditures across categories such as food, education, transportation, and utilities.

- **Household Size** – Number of family members, which influences financial decisions.

- **Education Rank & Binary Education Variable** – Households are classified into High Education (1) or Low Education (0).

- **Age of Household Head** – Analyzed to determine its impact on expenditure patterns.

## Exploratory Data Analysis (EDA)

Several analyses were conducted to understand financial behaviors:

- **Age vs. Expenditure Trends** – Younger households spend more on transportation and leisure, while older households allocate more to medical and housing expenses.

- **Income vs. Expenditure Relationship** – Higher-income groups save more proportionally, while lower-income groups have a higher spending-to-income ratio.

- **Spending Patterns by Income Level** – Very Low and Low-income households prioritize essential needs, whereas High-income households diversify spending across luxury and investment categories.

- **Pie Charts of Spending Breakdown** – Visualizing expenditure proportions for different income groups.

## Machine Learning Models & Key Findings

We applied Linear Regression and Random Forest Regression to predict household expenditures:

#### Linear Regression Model

**Findings**: There is a strong positive correlation between income and total expenses.

**R² Score**: Indicates that income explains most of the variance in household spending.

**Impact of Education**: Higher education reduces financial distress by promoting savings and efficient expenditure allocation.

#### Random Forest Regression Model

**Findings**: The model outperforms linear regression in predicting total expenses.

**Feature Importance**: Income is the strongest predictor, but education, household size, and savings potential also contribute significantly.

**Model Accuracy**: The non-linear approach reduces prediction errors, making it more effective for complex financial trends.

## NumPy Multi-Dimensional Analysis

To structure and analyze financial data efficiently, we used a NumPy multi-dimensional array containing:

- Total Household Income
- Total Expenses
- Savings

### Findings from NumPy Analysis:

- The structured approach helped compare spending trends across income groups.

- Household size and education levels impact disposable income, reinforcing financial literacy’s role in stability.

- Fast computations allowed for better pattern recognition in expenditure behavior.

## Key Insights

- **Households with higher income levels allocate a greater portion of their earnings to luxury and discretionary spending**, whereas lower-income households prioritize essential needs such as food and utilities.
- **Household size and education level significantly impact expenditure patterns**
- **The Random Forest model outperformed Linear Regression, suggesting that spending behavior is influenced by multiple non-linear factors.**
- **Higher education leads to greater financial stability and savings behavior.**



## Future Work

To enhance this study, future research could explore:

- **Regional or cultural differences** in spending behavior.

- **Impact of inflation and economic downturns** on financial stability.

- **Longitudinal financial behavior tracking** to predict wealth accumulation trends.

- **Developing a financial literacy tool** based on predictive modeling insights.



#### Brought to you by ~

Thet Mon Thet.
