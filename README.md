# Task 7 – Basic Sales Summary with SQLite & Python

## Objective
Query sales data from a SQLite database using Python, then display results and plot revenue by product.

## Steps Performed
1. Created a SQLite database `sales_data.db` with sample sales data.
2. Wrote Python code to:
   - Connect to the database.
   - Run an SQL `GROUP BY` query to calculate total quantity and total revenue.
   - Load results into Pandas DataFrame.
   - Print the results.
   - Plot revenue per product using Matplotlib.
3. Saved the bar chart as `sales_chart.png`.

## Files
- `sales_data.db` – SQLite database file containing sample sales data.
- `sales_chart.png` – Bar chart showing revenue by product.
- `sales_summary.ipynb` – Google Colab notebook with the full code.

## How to Run
1. Clone the repo:
   ```bash
   git clone <repo_link>
