# 🍕 Dominos SQL Data Analysis Project

## 📌 Project Overview
This project is based on analyzing pizza sales data using SQL.  
It includes database design, data analysis, and business insights generation.

The project simulates a real-world pizza store (like Dominos) and answers important business questions using SQL queries.

---

## 🗂️ Database Schema

The database consists of 4 main tables:

1. **Orders**
   - Order_ID
   - Order_Date
   - Order_Time

2. **Order_Details**
   - Order_Details_ID
   - Order_ID
   - Pizza_ID
   - Quantity

3. **Pizzas**
   - Pizza_ID
   - Pizza_Type_ID
   - Size
   - Price

4. **Pizza_Types**
   - Pizza_Type_ID
   - Name
   - Category
   - Ingredients

---

## 📊 Dataset Files

- `orders.csv`
- `order_details.csv`
- `pizzas.csv`
- `pizza_types.csv`

These datasets are used to create tables and perform SQL analysis.

---

## 📈 Key Business Questions Solved

### 🔹 Basic Analysis
- Total number of orders
- Total revenue generated
- Highest-priced pizza
- Most common pizza size
- Top 5 most ordered pizzas

### 🔹 Intermediate Analysis
- Category-wise pizza sales
- Orders distribution by hour
- Daily average orders
- Category distribution

### 🔹 Advanced Analysis
- Revenue contribution by category
- Cumulative revenue over time
- Top pizzas by revenue (category-wise)

---

## 🛠️ Technologies Used
- SQL (MySQL / PostgreSQL)
- Database Design (ER Diagram)
- CSV Dataset Handling

---

## 📁 Project Files

- `dominos_project.sql` → SQL queries
- `orders.csv` → Orders data
- `order_details.csv` → Order details data
- `pizzas.csv` → Pizza data
- `pizza_types.csv` → Pizza types data
- `project_presentation.pptx` → Project PPT
- `sql_queries.docx` → Documentation
- `er_diagram.png` → Database schema

---

## 🔗 ER Diagram
(https://github.com/Adesh2702/Dominos-SQL-Project/blob/main/er_diagram..png)

---

## 🚀 How to Run This Project

1. Create a database in MySQL/PostgreSQL
2. Import all CSV files into tables
3. Run the SQL script (`dominos_project.sql`)
4. Execute queries to get insights

---

## 💡 Key Learnings
- SQL Joins (INNER JOIN, etc.)
- Aggregate Functions (SUM, COUNT, AVG)
- Window Functions
- Data Analysis using SQL
- Real-world database design

---

## 👨‍💻 Author
**Adesh Kishor Dakhore**  
B.Tech CSE – Sandip University

---

## ⭐ Future Improvements
- Create dashboard using Power BI / Tableau
- Build web app using this database
- Add real-time data integration
