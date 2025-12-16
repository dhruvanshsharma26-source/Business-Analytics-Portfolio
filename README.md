# Superstore Sales & Profit Analysis  
Business Analytics & Predictive Modelling Project

## Overview
This project analyses a retail superstore dataset to uncover sales and profit drivers,
perform exploratory data analysis (EDA), and apply predictive modelling techniques
to understand factors influencing profitability.

The analysis follows a structured analytics workflow, including data cleaning,
visualisation, feature transformation, and regression modelling, with a strong
focus on business interpretation.

---

## Business Objective
To analyse historical retail transaction data and:
- Identify key patterns in sales and profit performance
- Understand how customer segments, regions, product categories, and discounts
  influence profitability
- Build a predictive model to assess relationships between key variables and profit

---

## Dataset
- **Source:** Superstore retail dataset (public dataset)
- **Records:** ~9,900 transactions
- **Features:** Orders, customers, regions, product categories, sales, discounts, profit

Key variables analysed include:
- Sales
- Profit
- Quantity
- Discount
- Segment
- Category
- Region
- Ship Mode

---

## Tools & Technologies
- **Python**
  - Pandas, NumPy – data manipulation and preprocessing
  - Matplotlib, Seaborn – data visualisation
- **Scikit-learn**
  - Linear Regression
  - Gradient Boosting Regressor
- **Jupyter Notebook / Deepnote**

---

## Methodology

### 1. Data Cleaning & Preparation
- Checked and confirmed absence of missing values
- Converted date columns to appropriate datetime formats
- Removed irrelevant or duplicate identifier columns
- Treated extreme outliers in Sales, Quantity, and Discount
- Encoded categorical variables for modelling purposes

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis using boxplots and scatterplots
- Sales and profit analysis across:
  - Regions
  - Customer segments
  - Product categories and sub-categories
  - Shipping modes
- Identified skewness, kurtosis, and outlier behaviour in key numerical variables

### 3. Predictive Modelling
- Built a **Linear Regression model** to analyse relationships between features and profit
- Evaluated model using:
  - Mean Squared Error (MSE)
  - R-squared (R²)
- Implemented a **Gradient Boosting Regressor** to analyse feature importance

---

## Key Insights
- Sales volume alone does not guarantee profitability; discounts strongly affect margins
- Certain product categories and sub-categories contribute disproportionately to profit
- Customer segment and regional differences influence sales patterns
- Extreme discounting can negatively impact profit despite higher sales volumes

---

## Model Results
- Linear Regression showed a very strong statistical fit on the processed dataset
- Feature importance analysis highlighted:
  - Sales
  - Discount
  - Product category
  - Quantity  
  as key contributors to profit behaviour

> Note: Model results are interpreted cautiously due to encoding choices and dataset characteristics.

---

## Business Recommendations
- Optimise discount strategies to protect profit margins
- Focus on high-performing product categories rather than pure volume growth
- Use customer segmentation to design targeted pricing and promotion strategies
- Monitor outliers and extreme transactions that distort profitability analysis

---

## Repository Structure
superstore-analytics-project/
│
├── data/
│ └── superstore_data.csv
│
├── notebooks/
│ └── superstore_analysis.ipynb
│
├── outputs/
│ └── visualisations/
│
├── summary.md
└── README.md

---

## Key Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Business insight generation
- Regression modelling
- Feature importance analysis
- Data visualisation
- Analytical storytelling

---

## Author
Business Analytics Graduate  
Interested in Data Analyst / Business Analyst / Analytics Consultant roles  

🔗 LinkedIn: www.linkedin.com/in/dhruvansh-sharma-45690b233 
📂 GitHub: superstore-analytics-project

---

## Disclaimer
This project is for academic and portfolio purposes.  
Insights and model results are based on the provided dataset and may not generalise
directly to real-world commercial environments.
