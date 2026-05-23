# Marketing Budget Optimization using Linear Regression

## Project Title
Marketing Budget Optimization using Linear Regression

---

# Business Problem

Companies invest heavily in multiple marketing channels such as TV, Radio, Social Media, and Digital Ads.  
However, businesses often struggle to determine which channel contributes the most to sales and revenue generation.

The main objective of this project is to:
- Analyze marketing spending patterns
- Understand the relationship between advertising channels and sales
- Build a Linear Regression model to predict sales
- Optimize marketing budget allocation
- Improve return on investment (ROI)

This project helps businesses make data-driven marketing decisions.

---

# Dataset Description

The dataset contains information about marketing spending across different advertising platforms and corresponding sales.

## Features Used

| Column Name | Description |
|---|---|
| TV | Amount spent on TV advertisements |
| Radio | Amount spent on Radio advertisements |
| Social_Media | Amount spent on Social Media campaigns |
| Digital | Amount spent on Digital advertisements |
| Sales | Total sales generated |

## Target Variable
- Sales

## Independent Variables
- TV
- Radio
- Social_Media
- Digital

The dataset is used to predict sales based on marketing spend.

---

# Data Cleaning Summary

The following data cleaning steps were performed before model building:

- Checked for missing values
- Verified data types
- Checked duplicate records
- Reviewed summary statistics
- Inspected outliers using visualizations
- Ensured numerical columns were properly formatted

The dataset was found suitable for regression analysis after cleaning.

---

# Exploratory Data Analysis (EDA) Insights

Several visualizations and statistical analyses were performed to understand the data.

## Key Insights

- TV advertising showed a strong positive relationship with sales.
- Radio advertisements also contributed positively to revenue generation.
- Social Media and Digital marketing channels influenced sales differently.
- Correlation analysis helped identify relationships among variables.
- Higher marketing expenditure generally increased sales performance.

## Visualizations Used

- Histograms
- Scatter plots
- Correlation heatmap
- Sales distribution plots

EDA helped understand which channels were more impactful.

---

# Regression Model Summary

A Multiple Linear Regression model was built using marketing channels as input variables.

## Steps Performed

1. Feature and target selection
2. Train-test split
3. Model training using Linear Regression
4. Prediction on test dataset
5. Model evaluation

## Model Used

- Multiple Linear Regression

The model predicts sales based on marketing spending patterns.

---

# Model Evaluation Results

The model performance was evaluated using standard regression metrics.

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Interpretation

- Lower MAE and RMSE indicate better prediction accuracy.
- Higher R² Score indicates better model performance.
- The model successfully captured relationships between marketing channels and sales.

---

# Coefficients Interpretation

Regression coefficients explain the impact of each marketing channel on sales.

## Interpretation Rules

- Positive coefficient:
  - Increasing spending increases sales.
  
- Negative coefficient:
  - Increasing spending decreases sales.

## Business Meaning

- Channels with larger positive coefficients contribute more strongly to sales growth.
- Channels with weaker coefficients may require budget optimization.

This analysis helps identify high-performing marketing channels.

---

# Budget Recommendation

Based on the regression analysis and EDA insights:

## Recommendations

- Increase budget allocation for channels with strong positive impact.
- Reduce spending on low-performing channels.
- Focus more on high ROI marketing campaigns.
- Continuously monitor campaign effectiveness.
- Use predictive analytics for future budget planning.

These recommendations can improve marketing efficiency and revenue generation.

---

# How to Run the Project

## Step 1: Clone Repository
## Step 2: Install Required libraries
pip install -r requirements.txt
## Step 3: Open Jupyter Notebook or Google colab
Run: marketing_budget_optimization.ipynb
## Step 4: Upload Dataset
upload the dataset csv file when prompted
## Step 5: Run all cells
Execute all notebook cells sequentially.

## Techonologies
- Python
- Pandas
- Numpy
- matplotlib
- Seaborn
- Google Colab

## Conclusion
This Project demonstrates how linear Regression can help businesses optimize marketing spending and improve decision making using data analytics.
git clone <repository_link>
