# SuperStore Sales Performance Analysis

### [View Final PDF Report](Super%20Store%20Sales%20Performance%20Analysis%20Report.pdf) | [View Full Code Notebook](EDA_superstore(by%20me).ipynb)

---

## 1. Project Objective
This report provides a comprehensive analysis of the SuperStore sales data from 2014 to 2017. The primary goal was to identify key drivers of profitability and uncover actionable insights to improve business performance.

---

## 2. Tools & Technologies
- **Python:** For data analysis and manipulation.
- **Pandas:** For data cleaning, transformation, and aggregation.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For Label Encoding.
- **Jupyter Notebook:** As the main environment.

---

## 3. Key Findings & Visualizations

#### Finding 1: Geographical Imbalance
The West region is the clear leader in both sales and profitability, while states like Texas and Pennsylvania are massive loss centers.
*(Yeh chart West/East/Central/South waala hai)*
<img width="688" height="335" alt="image" src="https://github.com/user-attachments/assets/9b58bc85-0742-4116-9e58-66ae880cb3bf" />
*(Yeh chart Top 10 States waala hai)*
<img width="666" height="275" alt="image" src="https://github.com/user-attachments/assets/787bbcdb-f1e7-413f-939b-6d64d50b4c18" />

#### Finding 2: Strong Seasonal Pattern
The business operates on a strong seasonal cycle, with sales consistently peaking in the final quarter (Q4) of each year.
<img width="678" height="310" alt="image" src="https://github.com/user-attachments/assets/fc41e950-2a8a-4753-a2cf-bcbdd23e63be" />

#### Finding 3: Discounts Drive Losses
A strong negative correlation exists between discounts and profit. Higher discounts are the primary cause of unprofitable sales.
<img width="1050" height="588" alt="image" src="https://github.com/user-attachments/assets/4969a544-1255-4efb-9467-30f208bf34e4" />

---

## 4. Key Business Recommendations

1.  **Conduct a Regional Profitability Audit:** Immediately investigate the low profit margins in the East region and create a turnaround plan for Texas, Pennsylvania, and Ohio.
2.  **Leverage Seasonality for Maximum Gain:** Begin holiday marketing campaigns in late Q3 to capitalize on the predictable Q4 sales peak and optimize inventory.
3.  **Implement a Smart Discounting Strategy:** Review and cap discount percentages for low-margin product categories and stop discounts on already loss-making products.
