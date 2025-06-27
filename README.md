# sales-summary-sqlite-python
# Task 6 – Basic Sales Summary using SQLite and Python 🛒📊

## 📌 Objective:
Use SQL inside Python to extract basic sales information like total quantity sold and total revenue, and visualize it using a simple bar chart.

---

## 🧰 Tools & Libraries Used:
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📁 Files Included:
- `sales_summary.ipynb` – Jupyter Notebook with complete code and output
- `sales_data.db` – SQLite database file with dummy sales data
- `sales_chart.png` – Bar chart showing revenue by product

---

## 🔍 Task Details:
1. Created a simple SQLite database (`sales_data.db`) with a single table: `sales`
2. Inserted dummy product sales data (Product A, B, C with quantity and price)
3. Ran SQL queries inside Python to get:
   - Total quantity sold per product
   - Total revenue per product (`quantity * price`)
4. Loaded results into a pandas DataFrame
5. Printed the summary table using `print(df)`
6. Plotted a bar chart of revenue using `matplotlib`
7. Saved the chart as `sales_chart.png`

---

## 📊 Output Sample:
```plaintext
   product  total_qty  revenue
0  Product A         13    260.0
1  Product B          9    135.0
2  Product C         15    180.0
