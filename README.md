# Personal_Expenses_Tracker
This file provides a clear and simple overview, links to files, and summarizes the project.
This project is a comprehensive data-driven solution designed to help users, specifically students, monitor and analyze their spending habits. It includes data creation, exploratory data analysis (EDA), predictive modeling, and visualizations using Python. The data is tailored to reflect a typical student's expenses, offering insights into financial patterns and forecasting future spending trends.

---

## Project Structure

- **Data Creation**: Generates a realistic dataset of expenses, designed from a student’s perspective.
- **Complete Data Lifecycle**: Processes the generated data, performs EDA, and builds predictive models to forecast expenses.
- **Dataset**: Contains the final dataset used for analysis.

---

## Files

- **[Data Creation (Notebook)](./Python/data_creation.ipynb)**: Jupyter Notebook to create a realistic expense dataset based on student spending patterns.
- **[Complete Data Lifecycle (Notebook)](./Python/data_lifecycle.ipynb)**: Jupyter Notebook containing data cleaning, EDA, visualizations, and predictive modeling.
- **[Dataset](./Python/dataset.csv)**: The final dataset used for analysis.

---

## Key Insights

### 1. Income vs. Expense Overview
   - Monthly income is consistent, with expenses generally staying below income, allowing for savings.
   - Certain months show expenses approaching income, indicating high spending periods.

### 2. Essential vs. Non-Essential Spending
   - **Essential** expenses (e.g., rent, groceries) dominate monthly spending.
   - **Non-essential** expenses (e.g., entertainment, dining out) vary by month, especially around holidays and weekends.

### 3. Spending Patterns by Day of the Week
   - Higher spending on weekends, particularly Saturdays, likely due to leisure activities.
   - Lower spending on weekdays aligns with a student budget focused on essentials.

### 4. Monthly Spending Trends
   - Spending trends fluctuate slightly each month, influenced by essential expenses and occasional higher non-essential costs.

### 5. Cumulative Income vs. Cumulative Expenses
   - Income consistently exceeds expenses, indicating positive cash flow.
   - This surplus provides a stable foundation for budgeting and saving.

### 6. Forecasting Future Expenses
   - Using SARIMA, a monthly expense forecast was generated for the next 12 months.
   - The forecast suggests stable expenses with slight seasonal fluctuations, helping students plan for high-cost months.

---

## Visualizations

### Key Charts:
1. **Total Income vs. Total Expenses**: Compares monthly income and expenses.
2. **Essential vs. Non-Essential Spending Pie Chart**: Shows the proportion of essential to non-essential expenses.
3. **Monthly Spending Heatmap**: Displays average spending by day of the week for each month.
4. **Cumulative Income vs. Cumulative Expenses Line Chart**: Shows long-term financial health by tracking income and expenses over time.
5. **Monthly Expense Forecast**: Forecasts future expenses, allowing users to anticipate high-expense months.

---

## Technologies Used

- **Python** for data processing, analysis, and modeling
- **Jupyter Notebook** for developing, documenting, and sharing the code
- **SARIMA Model** for expense forecasting

---

## How to Use

1. **Data Creation**: Run the [Data Creation Notebook](./Python/data_creation.ipynb) to generate the dataset.
2. **Complete Analysis**: Use the [Data Lifecycle Notebook](./Python/data_lifecycle.ipynb) to perform analysis, visualize trends, and make predictions.
3. **Dataset**: Refer to the [Dataset](./Python/dataset.csv) if you want to skip data generation and jump to analysis.

---

## Final Thoughts

The **Personal Expense Tracker** is designed to provide valuable financial insights for students. It helps users track, optimize, and forecast their expenses, empowering them to make data-driven financial decisions.
