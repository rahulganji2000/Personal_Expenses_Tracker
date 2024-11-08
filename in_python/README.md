# Personal Expense Tracker Project

This project aimed to create a comprehensive data-driven solution to analyze and predict monthly expenses, helping users monitor their spending patterns, identify savings opportunities, and make more informed financial decisions.

---
## Project Files

- **[Data Creation (Notebook)](./Python/data_creation.ipynb)**: Jupyter Notebook to create a realistic expense dataset based on student spending patterns.
- **[Complete Data Lifecycle (Notebook)](./Python/data_lifecycle.ipynb)**: Jupyter Notebook containing data cleaning, EDA, visualizations, and predictive modeling.
- **[Dataset](./Python/income_and_utilities_expense_tracker.csv)**: The final dataset used for analysis.

---
## Summary of Analysis

### Historical Expense Analysis

#### Income vs. Expense Overview
- Monthly income consistently exceeded expenses, creating room for savings. However, some months had expenses approaching income, reducing the savings margin.

#### Essential vs. Non-Essential Spending
- **Essential expenses** (e.g., rent, utilities) dominated spending, while **non-essential expenses** (e.g., entertainment, dining out) fluctuated more. High peaks in non-essential spending during certain months indicated opportunities to optimize discretionary expenses.

#### Category-Wise Spending
- The majority of expenses were on food and utilities, aligning with a typical student’s cost-of-living breakdown. Entertainment and shopping costs were generally lower but increased periodically, often around holidays and events.

#### Spending Patterns by Day of the Week
- Higher spending occurred on weekends, particularly Saturdays, for non-essential activities like dining out and entertainment. Lower spending on weekdays reflected a focused approach to budgeting essentials during the week.

#### Long-Term Trends
- Cumulative income consistently outpaced cumulative expenses, reflecting good financial health. Managing discretionary expenses further strengthens long-term savings potential.

---

## Predictive Modeling with SARIMA

### Monthly Expense Forecast
- The **SARIMA model** provided a stable forecast for monthly expenses, highlighting a consistent pattern with minor seasonal fluctuations.
- **Confidence Intervals**: These suggest that while monthly expenses remain stable, some uncertainty exists, especially for longer-term projections. This range helps in planning for potential expense increases or decreases.

### Seasonal Effects
- Seasonal expense peaks in specific months indicate recurring high-cost periods, helping users plan by allocating extra funds or reducing non-essential expenses during these months.

---

## Actionable Insights and Recommendations

### For Expense Optimization and Financial Planning

1. **Optimize Discretionary Spending**:
   - Given higher non-essential spending on weekends, users can set weekly or monthly limits on dining out and entertainment. Allocating a fixed amount for non-essential expenses each month helps control costs while maintaining flexibility for leisure activities.

2. **Focus on High-Cost Months**:
   - Certain months had higher expenses, possibly due to utilities, seasonal shopping, or entertainment. Preparing for these months by adjusting discretionary spending or setting aside additional savings can help manage these periods better.

3. **Budget Buffer for Seasonal Variation**:
   - The forecast suggests periodic expense fluctuations. Users could maintain a buffer in their budget to accommodate these spikes, reducing reliance on savings during high-cost periods.

4. **Savings Allocation**:
   - With income consistently exceeding expenses, allocating a specific percentage of income directly to savings or investments each month can help maintain financial health. Setting a savings goal based on forecasted expenses supports disciplined financial planning.

---

## Aligning with Job Requirements

This analysis aligns with the job description by:

- **Analyzing Trends**: We identified both monthly and seasonal expense trends, providing insights into user spending habits and enabling better budgeting.
- **Predictive Modeling**: The SARIMA model for monthly expense forecasting demonstrates proficiency in predictive analytics, relevant for supporting data-driven recommendations.
- **Actionable Financial Insights**: The analysis provided clear recommendations, key for roles focused on delivering customer value and improving financial decision-making.
- **Data Visualization**: The visualizations (line charts, heatmaps, and bar charts) effectively communicated data patterns, enhancing insights accessibility, aligning with the need for strong data visualization skills.

---

## Final Thoughts

This project successfully demonstrates the ability to gather insights, predict future trends, and provide practical recommendations. It reflects a blend of **technical skill in data analysis and predictive modeling** with a focus on **real-world financial applications**. These insights support user budgeting and financial planning, aligning with the job's emphasis on providing valuable, data-driven recommendations for customer success and improved financial health.

This analysis can serve as a foundation for future improvements, such as incorporating additional data sources (e.g., holiday spending effects), adding more advanced predictive techniques, or integrating it into a personal finance dashboard.
