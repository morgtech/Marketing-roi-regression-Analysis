# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project analyzes the relationship between marketing expenditure and sales performance using Simple Linear Regression. The objective is to identify which marketing channel has the strongest impact on sales and provide a data-driven recommendation for marketing budget allocation.

The analysis includes data cleaning, exploratory data analysis (EDA), correlation analysis, regression modeling, diagnostic testing, and business interpretation of results.

---

## Project Objectives

* Load and clean the marketing dataset
* Explore the data using summary statistics and visualizations
* Identify the advertising channel most strongly correlated with Sales
* Build a Simple Linear Regression model using Ordinary Least Squares (OLS)
* Evaluate regression assumptions
* Interpret model outputs in a business context
* Recommend the most effective marketing channel for investment

---

## Dataset Variables

| Variable     | Description                          |
| ------------ | ------------------------------------ |
| TV           | TV advertising expenditure           |
| Radio        | Radio advertising expenditure        |
| Social_Media | Social media advertising expenditure |
| Sales        | Product sales                        |

---

## Methodology

The project followed the steps below:

1. Data Loading and Inspection
2. Missing Value Handling
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Variable Selection
6. Simple Linear Regression Modeling
7. Model Evaluation
8. Diagnostic Testing
9. Business Interpretation and Recommendations

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* SciPy
* Jupyter Notebook

---

## Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

---

## Running the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd Marketing-ROI-Regression-Analysis-analysis
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
regression_analysis.ipynb
```

5. Run all cells sequentially.

---

## Key Findings

* TV advertising exhibited the strongest relationship with Sales and was selected as the predictor variable for the regression model.
* The Simple Linear Regression model achieved an R-squared value of **0.999**, indicating that approximately **99.9% of the variation in Sales** is explained by TV advertising expenditure.
* The TV advertising coefficient was **3.5615**, suggesting that for every one-unit increase in TV advertising expenditure, Sales are expected to increase by approximately **3.56 units**, holding all other factors constant.
* The TV advertising variable was highly statistically significant (**p < 0.001**), confirming a strong positive relationship between TV advertising and Sales.
* Residual diagnostic tests indicated that the assumptions of linear regression were reasonably satisfied, supporting the validity of the model.


---

## Recommendation

Based on the regression results, TV advertising should be prioritized when allocating marketing resources. The model demonstrates that TV advertising has a strong and statistically significant impact on Sales, explaining nearly all observed variation in the target variable (R² = 0.999).

Therefore, increasing investment in TV advertising is expected to generate the greatest return on marketing expenditure compared to the other marketing channels evaluated in this analysis.

---

## Repository Structure

```text
│morgtech/marketing-roi-regression-analysis/
├── README.md
├── marketing_and_sales_data_evaluate_lr.csv
├── regression_analysis.ipynb
└── requirements.txt
```

---

## Author

Godwill Morgan Lekwa
