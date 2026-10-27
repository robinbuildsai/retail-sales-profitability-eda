# Retail Sales & Profitability Analysis (EDA)

## Overview
An exploratory data analysis project using Python to study retail sales, profit, customers, product categories, and discount patterns.

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Notebook
Open `retail_sales_profitability_eda_github.ipynb` in Jupyter Notebook or JupyterLab.

## Dataset
The notebook expects a file named `retail-orders.csv` in the same directory as the notebook.

**Important:** The dataset was not included with this notebook. Add it only if you have permission to redistribute it. If it is private or licensed, include the official source or access instructions instead.

## Questions explored
- Missing values and duplicate records
- Sales and profit by category and sub-category
- Monthly and yearly sales trends
- Customer-level sales and profitability
- Relationship between discounts and profit
- Investigation of loss-making products

## Key findings
- Technology was the leading category by total sales and total profit in the analysed dataset.
- Furniture had a relatively low overall profit margin despite substantial sales.
- Higher discount groups were associated with weaker profitability, especially in the Tables sub-category.
- Product-level results varied, so discount should not be treated as the sole cause of losses.

## Run locally
1. Install Python and Jupyter.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Place `retail-orders.csv` beside the notebook.
4. Launch Jupyter and open the notebook.

## Notes
This is descriptive EDA. Observed relationships are not proof of causation, and small product-level groups should be interpreted cautiously.
