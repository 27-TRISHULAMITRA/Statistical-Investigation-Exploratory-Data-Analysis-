📊 Statistical Investigation & Hypothesis Testing Using Python


📌 Project Overview

This project focuses on performing a comprehensive statistical investigation on customer data to uncover spending patterns, customer behavior, and relationships between demographic factors. The analysis combines Exploratory Data Analysis (EDA), descriptive statistics, data visualization, and statistical hypothesis testing to validate business assumptions using data-driven evidence.



🎯 Project Objectives

Understand customer demographics and spending behavior.
Perform descriptive statistical analysis on key variables.
Visualize data distributions and relationships.
Formulate business questions as statistical hypotheses.
Apply appropriate statistical tests to validate assumptions.
Generate actionable insights from both EDA and hypothesis testing.


🛠️ Tools & Technologies

Python
Pandas – Data Manipulation & Analysis
NumPy – Numerical Computation
Matplotlib – Data Visualization
Seaborn – Statistical Visualization
SciPy Stats – Hypothesis Testing & Statistical Analysis
Jupyter Notebook

📂 Project Workflow

1️⃣ Data Understanding & Inspection
Loaded customer dataset.
Examined data structure and data types.
Identified categorical and numerical variables.
Checked for missing values and inconsistencies.

2️⃣ Descriptive Statistics

Calculated:

Mean
Median
Standard Deviation

For:

Age
Monthly Spend
Days Since Last Interaction

Key Insights

Age distribution was approximately symmetric.
Monthly Spend showed positive skewness due to high-spending customers.
Days Since Last Interaction exhibited high variability among customers.
3️⃣ Exploratory Data Analysis (EDA)


Performed visual analysis using:

Histograms
Box Plots
Count Plots
Scatter Plots
Correlation Analysis

Objectives

Detect outliers.
Understand distributions.
Explore relationships between variables.
Identify trends and patterns.

4️⃣ Bivariate Analysis

Analyzed relationships between:

Gender vs Monthly Spend

Education Level vs Monthly Spend

Marital Status vs Pets Owned

Age vs Days Since Last Interaction

State vs Monthly Spend

🧪 Statistical Hypothesis Testing

Test 1: Independent Samples t-Test

Business Question: Do males and females spend differently?

H₀: Average Monthly Spend is equal for males and females.
H₁: Average Monthly Spend differs between males and females.

Result

p-value > 0.05
Failed to reject H₀

Conclusion
There is no statistically significant difference in spending behavior between male and female customers.

Test 2: One-Way ANOVA

Business Question: Does education level impact average monthly spending?

H₀: Mean Monthly Spend is equal across all education levels.
H₁: At least one education level differs.

Result

p-value > 0.05
Failed to reject H₀

Conclusion
Education level does not significantly influence customer spending.

Test 3: Chi-Square Test of Independence

Business Question: Is marital status related to pet ownership?

H₀: Marital Status and Pets Owned are independent.
H₁: Marital Status and Pets Owned are dependent.

Result

p-value < 0.05
Rejected H₀

Conclusion
A significant relationship exists between marital status and pet ownership.

Test 4: Pearson Correlation Test

Business Question: Are older customers less active?

H₀: No relationship exists between Age and Days Since Last Interaction.
H₁: A relationship exists.

Result

p-value > 0.05
Failed to reject H₀

Conclusion
Customer age has no statistically significant relationship with interaction frequency.

Test 5: One-Way ANOVA

Business Question: Does customer spending vary by state?

H₀: Average Monthly Spend is equal across all states.
H₁: At least one state's average spending differs.

Result

p-value > 0.05
Failed to reject H₀

Conclusion
Customer spending patterns do not significantly differ across states.

📈 Key Business Insights

Customer spending behavior is largely consistent across gender, education level, and state.

Marital status significantly influences pet ownership patterns.

Age is not a reliable indicator of customer engagement.

A small group of high-value customers contributes disproportionately to spending levels.

Statistical testing helped validate findings observed during exploratory analysis.


🚀 Skills Demonstrated

Data Cleaning & Inspection

Exploratory Data Analysis (EDA)

Descriptive Statistics

Data Visualization

Hypothesis Testing

Statistical Interpretation

Business Problem Solving

Python for Data Analytics


📌 Outcome

This project demonstrates how statistical methods can be used alongside exploratory data analysis to transform business questions into measurable insights and support evidence-based decision-making.
