Sales Data Analysis using SQLite and Python

connecting to a SQLite database (`sales_data.db`) using Python, 
execute SQL queries, and analyze sales data with pandas and matplotlib.

Steps Performed
1. Connected to SQLite Database
   - Used Python's built-in `sqlite3` library to connect to `sales_data.db`.

2. Executed SQL Queries
   - Query 1: Summarized sales per product (total quantity and total revenue).  
   - Query 2: Calculated overall totals (sum of all quantities and total revenue).  

3. Loaded Results into Pandas 
   - Used `pandas.read_sql_query` to load query results into DataFrames for easier analysis.

4. Displayed Output
   - Printed sales summary and overall totals in tabular format.

5. Visualized Results  
   - Created a **bar chart** showing revenue per product using `matplotlib`.  
   - Results can be saved as images (e.g., `sales_chart.png`).  
   
Tools Used
- Python 3.x  
- Libraries: `sqlite3`, `pandas`, `matplotlib`  
- Jupyter Notebook (to run `.ipynb` files)

