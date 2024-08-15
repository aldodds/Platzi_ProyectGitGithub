# Sales Data Analysys

## Introduction

### Project objective
The objective of this project is to analyze sales and revenue data from a synthetically generated dataset to gain insights that can aid in business decision-making. The analysis includes descriptive statistics, variable type adjustments, detection and treatment of missing data, and identification of outliers.

### Tools used
Python, Pandas, NumPy, Matplotlib, Seaborn, JupyterLab.

## Method
### Data description
Synthetic sales and income data were generated for a 12-month period (365 days) with the following characteristics:
- `Date`: Daily date range
- `Product`: Four different products labeled 'A,' 'B,' 'C,' and 'D'
- `Sales`: Random number of daily sales between 100 and 1,000
- `Revenue`: Random daily income between 1,000 and 5,000

### Variable type adjustments
The Date, Product, Sales, and Revenue variables have been confirmed to have the correct data types, making further analysis easier.

### Missing data treatment
No missing data were identified. The forward fill (ffill) method is available, ensuring data continuity

### Identification of Outliers
Several outliers were identified in both sales and income. These outliers were analyzed to understand possible reasons behind them.

## Conclusions
1. The variability in sales and revenue suggests that the business experiences different levels of demand or success on different days. This could be influenced by various factors such as promotions, seasonality, or market conditions.
2. The low correlation suggests that there is no simple linear relationship between `Sales` and `Revenue`. This does not mean there is no relationship at all, but rather that the relationship may be more complex than what Pearson's correlation can detect.
3. The analysis suggests that June is a key month for sales and revenue.

## Contributions
Suggestions and contributions are welcome. Please open an issue or pull request to propose changes.
    

