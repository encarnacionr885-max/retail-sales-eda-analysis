# Retail Sales EDA Analysis

## Project Overview
This project explores the Superstore dataset to understand sales, profit, and discounts across product categories. The main goal is to identify profitability gaps and provide actionable recommendations, with a particular focus on the Furniture category.

## Folder Structure

retail-sales-eda-analysis/
│
├── data/ # Dataset files
│ └── Superstore.csv
├── notebooks/ # Jupyter Notebook
│ └── eda_analysis.ipynb
├── images/ # Charts and visualizations
│ ├── profit_by_category.png
│ ├── sales_by_category.png
│ ├── discount_by_category.png
│ └── profit_margin_by_category.png
└── README.md # Project overview


## Key Insights
- Technology and Office Supplies have the highest profit margins.
- Furniture generates strong sales but low profit.
- Tables and Bookcases are the main sources of losses within Furniture.
- Discounts are not the main issue; structural and operational factors (production costs, pricing, supply chain) drive low margins.

## Recommendations
### 1) Review Costs in Production Process
Focus on Tables and Bookcases. Consider redesigning elements, optimizing production and logistics, and reviewing supplier prices. Also, review the supply chain across all sub-categories to improve overall performance.

### 2) Reevaluate Pricing Strategy
Furniture shows strong demand. Prices could be adjusted strategically. Running a price elasticity analysis can determine whether small price increases improve profitability without reducing demand.

### 3) Optimize Discount Policy
Avoid applying discounts to unprofitable sub-categories. Decisions should be strategic to increase sales while protecting margins. Establish a minimum margin threshold to prevent future losses.

### 4) Rationalize the Product Portfolio
If Tables or Bookcases continue generating losses, consider discontinuing or redesigning them. Focus on profitable products like Chairs and Furnishings, and apply marketing strategies and planned discounts to boost profitability.

### Executive Note
Implementing these measures could significantly increase Furniture’s profitability, narrowing the gap with Technology and Office Supplies while keeping overall sales strong.

## How to Use
1. Open `notebooks/eda_analysis.ipynb` in Jupyter Notebook or VS Code.
2. Ensure `Superstore.csv` is in the `data/` folder.
3. All charts are stored in the `images/` folder and can be displayed directly in the notebook.

## Author
**Ricardo Encarnacion**  
Portfolio Project – Retail Sales EDA Analysis