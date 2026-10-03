Walmart Black Friday Sales Analysis 📊

An exploratory data analysis project using Walmart Black Friday sales data to understand customer purchasing behaviour and identify patterns across demographics and customer segments.

🎯 Business Objective

The analysis examines how factors such as gender, age, marital status, city category, occupation, and product category relate to customer purchase amounts.

It also uses 95% confidence intervals to compare average spending across customer groups.

🛠️ Tools & Technologies

Python

Pandas – Data manipulation and analysis

NumPy – Numerical calculations

Matplotlib – Visualization

Seaborn – Statistical visualization

SciPy – Confidence interval calculations

Google Colab

📊 Dataset

Transactions: 550,068

Original columns: 10

Age groups: 7

City categories: 3

Product categories: 20

Gender: Male / Female

Occupation codes: 0–20

🔍 Analysis Performed

Data Understanding

Dataset shape and structure

Data types

Unique-value analysis

Missing-value analysis

Duplicate analysis

Descriptive statistics

Exploratory Data Analysis

Purchase distribution

Gender distribution

Age-group distribution

Occupation distribution

City-category distribution

Marital-status distribution

Purchase boxplots

Demographic vs purchase comparisons

Correlation heatmap

Outlier detection

Statistical Analysis

Average purchase comparison by gender

95% confidence intervals for male vs female spending

95% confidence intervals for married vs unmarried spending

Age-group confidence interval comparison

Central Limit Theorem-based interpretation

💡 Key Findings

Average purchase amount is approximately ₹9,263.97.

Purchase values range from ₹12 to ₹23,961.

The 26–35 age group is the largest customer segment.

City Category B has the highest customer representation.

Male customers have a higher average purchase than female customers in this dataset:

Male: ₹9,437.53

Female: ₹8,734.57

The 95% confidence intervals for male and female average purchases do not overlap.

The confidence intervals for married and unmarried customers overlap, indicating similar average spending patterns.

Purchase amounts are positively skewed, with a relatively small number of high-value purchases.

2,677 observations (0.49%) were identified as purchase outliers using the IQR method and were retained for analysis.

📌 Business Applications

The analysis can support:

Customer segmentation

Age-focused promotions

Personalized marketing

Product recommendations

Loyalty programs

Inventory planning

High-value customer identification

🚀 Future Scope

Formal hypothesis testing such as two-sample t-tests

Customer-level purchase aggregation

Product-category level revenue analysis

Customer lifetime value analysis

Predictive purchase modelling

RFM/customer segmentation

Interactive Power BI dashboard

📁 Project Structure

Walmart-Black-Friday-Analysis/
│
├── Walmart_Analysis.ipynb
├── walmart_data.csv
├── Walmart_Black_Friday_Analysis_README.md
└── Walmart_Black_Friday_Analysis_Detailed_Report.pdf

👤 Author

Aditya Kale
Data Analytics | Python | SQL | Power BI
