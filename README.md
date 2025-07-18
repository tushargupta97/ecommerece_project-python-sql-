
# 📊 Python + SQL E-commerce Data Analysis

This project demonstrates how to use Python in combination with SQL to perform exploratory data analysis (EDA) on an e-commerce dataset. It leverages SQL queries to extract data from a relational database and Python for data manipulation and visualization.

---

## 📁 Project Structure

- **Jupyter Notebook**: `python+sql_ecommerce.ipynb`
- **Tools Used**:
  - **SQL** (via MySQL connector)
  - **Python Libraries**:
    - `pandas` – Data manipulation
    - `numpy` – Numerical operations
    - `matplotlib`, `seaborn` – Data visualization
    - `mysql.connector` – Connect to MySQL database

---

## 🔍 Key Features

- **SQL-Based Data Extraction**:
  - Listing all unique cities where customers are located.
  - Counting orders placed in specific years.
  - Aggregating order, product, and payment data.

- **Visual Data Insights**:
  - Generating bar plots, histograms, and trend lines using `matplotlib` and `seaborn`.

- **Real Database Connection**:
  - Connection to a MySQL database using `mysql.connector`.
  - Efficient JOIN operations to combine multiple tables such as `orders`, `customers`, `order_items`, `payments`, and `products`.

---

## 🚀 How to Run

1. **Set up a MySQL server** and import your e-commerce dataset into it.
2. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn mysql-connector-python
   ```
3. Update your MySQL connection credentials in the notebook:
   ```python
   mysql.connector.connect(
       host="your_host",
       user="your_username",
       password="your_password",
       database="your_database"
   )
   ```
4. Run the notebook `python+sql_ecommerce.ipynb` in JupyterLab or VSCode.

---

## 📈 Sample Analysis Tasks

- Total revenue per year
- Most purchased products
- Customer city distribution
- Monthly order trends
- Payment method breakdown

---

## 🧠 Skills Demonstrated

- Writing complex SQL JOIN and aggregation queries.
- Integrating SQL with Python for dynamic data analysis.
- Creating meaningful visualizations from relational data.

---

## 📬 Contact

For any queries or feedback, feel free to reach out via email or GitHub.


Gmail - guptatushar0907@gmail.com
Github - https://github.com/tushargupta97
