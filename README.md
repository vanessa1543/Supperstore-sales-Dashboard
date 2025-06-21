# Superstore Sales Dashboard - EDA & Visualization

##  Project Overview

This project explores and visualizes sales data from a retail superstore to uncover insights about revenue performance, regional trends, product profitability, and customer segmentation. The analysis was performed using Python in a Jupyter Notebook environment.

The goal is to demonstrate skills in data cleaning, exploratory data analysis (EDA), and building a visually compelling and insight-rich sales dashboard.

---

##  Key Insights

1. The West Region Generates the Highest Sales

An analysis of regional performance revealed that the West consistently outperformed other regions in terms of total sales. However, when factoring in profit margins, the South often delivers more balanced performance due to lower discounting and better cost-efficiency. This suggests that while volume is high in the West, profitability strategies may need refining.

2. Product Discounts Reduce Overall Profitability

There is a negative correlation between discounts and profit. As discount percentages increase (especially above 30%), profit drops significantly, even turning negative for many transactions. A scatter plot of Discount vs Profit clearly shows that high discounts are frequently associated with financial losses. This indicates the need for a more strategic discounting policy to protect margins.

3. Specific Sub-Categories Drive Losses

Sub-categories such as Tables, Bookcases, and Binders show consistent negative profitability, particularly when sold with high discounts. While these products may be top sellers in terms of units or revenue, they are not contributing positively to the bottom line. Profit-focused reviews of pricing and supplier cost for these products are recommended.

4. Top Products Drive a Large Share of Revenue

A small number of products account for a disproportionately high share of total sales. The top 10 best-selling items contribute significantly more revenue than the rest, suggesting a Pareto effect (80/20 rule). These products should be prioritized in marketing and inventory planning due to their consistent performance.

5. Seasonal Trends Show Strong Sales in November and December

When grouped by order month, sales data shows noticeable spikes in November and December. This aligns with year-end sales campaigns, Black Friday, and holiday shopping behavior. Businesses can take advantage of this seasonal boost by launching targeted promotions and ensuring stock availability during Q4.

6. Office Supplies Generate High Volume, but Lower Profit

The Office Supplies category contributes a large number of transactions and overall sales, but profit margins are lower compared to Technology. This indicates a volume-driven category, where cost control and upselling may be required to increase profitability.

7. Top 10 Products Account for a Large Share of Revenue

Analysis of product-level sales shows that the Top 10 best-selling products generate a significant portion of total revenue, indicating a concentration of demand in a small set of items. These products include [insert examples if you like], and most of them belong to the Technology and Office Supplies categories.
---

##  Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas (data manipulation)
- Matplotlib & Seaborn (static visualizations)
- Plotly (interactive charts)
- NumPy

---

##  Project Structure

```bash
Superstore-Sales-Dashboard/
│
├── Superstore.csv              # Dataset
├── Sales_Dashboard.ipynb       # Main analysis notebook
├── requirements.txt            # Dependencies
└── README.md                   # Project summary (this file)
