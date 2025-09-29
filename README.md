# E-Commerce Growth Insights with SQL Window Functions  

![cover](https://raw.githubusercontent.com/panwarnalini-hub/sql-window-functions-ecommerce/main/cover.png)  

##  Project Overview  
This project explores **SQL Window Functions** in a realistic **e-commerce business scenario**.  
As a Data Analyst, your role is to uncover insights about customer behavior, employee performance, and sales trends.  

The project demonstrates how SQL can be applied to business-driven questions similar to **Kaggle-style challenges**.  

---

## Dataset  
A fictional `Orders` table was created with the following columns:  

- **OrderID** – unique identifier for each transaction  
- **CustomerID** – customer who placed the order  
- **EmployeeName** – sales rep handling the order  
- **Region** – customer region  
- **OrderDate** – date of purchase  
- **Amount** – transaction amount  

---

## Business Questions  

### 🔹 Customer Insights  
- What was each customer’s first purchase?  
- What was their most recent purchase?  
- How much has each customer spent in total over time?  

### 🔹 Employee Insights  
- Running total of sales per employee  
- Which employees are the top performers ranked by sales?  
- What are the top 2 sales handled by each employee?  

### 🔹 Trend Insights  
- How does an employee’s sales change month over month?  
- Which customers spent the most each month, and how do they rank against others?  
- What were the best and worst sales recorded for each employee?  

---

## SQL Concepts Used  
- **Window Functions**: `ROW_NUMBER`, `RANK`, `LAG`, `FIRST_VALUE`, `LAST_VALUE`  
- **Aggregations** with partitions  
- **Running totals** and **month-over-month changes**  
- **Ranking customers and employees** by sales  

---

## Key Learnings  
- Applied **SQL Window Functions** in realistic business scenarios  
- Gained insights into **customer loyalty, employee performance, and sales trends**  
- Built a project that can serve as a **portfolio piece** for data analyst / data engineer roles  

---

## Files in Repository  
- `E-Commerce-Growth-Insights.ipynb` → Jupyter Notebook with SQL code & analysis  
- `cover.png` → Project cover image  

---

## How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/panwarnalini-hub/sql-window-functions-ecommerce.git
