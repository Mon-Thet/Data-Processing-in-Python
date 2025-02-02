# Data-Processing-in-Python
## Understanding Household Income & Spending

### Project Overview

This project examines household income and expenditure patterns, exploring how families across different income levels allocate their resources. By leveraging data analysis and machine learning techniques, this project aims to provide insights into spending behaviors and develop models that can predict future expenditures based on key economic and demographic variables.

### Dataset Overview

The dataset contains comprehensive information on household earnings, expenses, family size, education, and assets. The key variables analyzed include:

Income Levels – Categorized into Low, Medium, and High based on quantiles.

Total Expenses – Summarizing expenditures across categories such as food, education, transportation, and utilities.

Household Size – The number of individuals in a household, which impacts spending behavior.

Education Rank – The highest level of education attained by the household head, potentially influencing financial decision-making.

### Project Setup

To replicate this analysis, follow these steps:

#### Install the Required Libraries

Ensure that you have the necessary Python libraries installed by running:

`pip install -r requirements.txt`

#### Execute the Script

Place the dataset in the appropriate directory and execute the script with:

`python income_vs_expenditure_analysis.py`

The script will generate visualizations, statistical summaries, and model predictions.

### Methodology

The research methodology follows a structured process:

Data Cleaning – Removal of incomplete records and financial inconsistencies to ensure data integrity.

Exploratory Data Analysis (EDA) – Employing visual tools such as bar charts, pie charts, and boxplots to identify spending patterns across income levels.

Feature Engineering – Incorporating education level and household size as key predictors for expenditure analysis.

Model Development – Implementing Linear Regression and Random Forest to predict household expenditure based on income and other factors.

Model Evaluation – Assessing predictive accuracy using R² scores and Mean Squared Error (MSE) to determine the effectiveness of the models.

### Key Insights

Households with higher income levels allocate a greater portion of their earnings to luxury and discretionary spending, whereas lower-income households prioritize essential needs such as food and utilities.

Household size and education level significantly impact expenditure patterns.

The Random Forest model outperformed Linear Regression, suggesting that spending behavior is influenced by multiple non-linear factors.

### Conclusion
This research provides valuable insights into household financial behavior, which can be applied in economic policy-making, financial planning, and consumer behavior analysis. Future studies can incorporate additional factors such as regional differences and economic conditions to enhance predictive accuracy.

#### Brought to you by ~

Thet Mon Thet.