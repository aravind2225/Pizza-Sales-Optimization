# 🍕 Pizza Sales Analysis – Business Insights with Power BI  

## 📌 Project Overview  
Play Pizza, a pizza company, was experiencing declining profits despite steady sales.  
As a **Data Analyst**, I conducted a **sales analysis using SQL + Power BI** to uncover insights, optimize decision-making, and recommend strategies for growth.  

This project demonstrates the **end-to-end analytics workflow**: data collection, cleaning, transformation, DAX calculations, visualization, and business insights.  

---

## 🎯 Client Requirements  
- Total Revenue for a given time period  
- Average Order Value  
- Total Pizzas Sold  
- Total Orders  
- Average Pizzas per Order  
- Daily & Monthly trends of orders  
- Revenue contribution by **pizza category** and **pizza size**  
- Top 5 sellers by revenue, orders, quantity  
- Bottom 5 sellers by revenue, orders, quantity  

---

## 🔎 Data Workflow  
1. **Data Collection** – Dataset extracted from the company’s order records.  
2. **SQL Server** – Data loaded into SQL for query-based insights.  
3. **Power BI** – Data imported for cleaning, transformation, and visualization.  
4. **Data Cleaning**:  
   - Promoted headers  
   - Converted column data types  
   - Replaced inconsistent values  
   - Removed duplicates  
5. **Transformation & Feature Engineering**:  
   - Extracted **Day & Month** from order date  
   - Added **dayNum** & **monthNum** using DAX  
6. **Measures (DAX)**:  
   - `Total Revenue` = SUM of purchase amounts  
   - `Average Order Value` = Revenue ÷ Total Orders  
   - `Total Pizzas Sold` = SUM of quantities  
   - `Total Orders` = DISTINCT count of order IDs  

---

## 📊 Dashboard Visuals  
- **Bar Chart** – Daily order trends  
- **Line Chart** – Monthly revenue trends  
- **Funnel Chart** – Pizzas sold by category  
- **Horizontal Bar Chart** – Best & worst sellers  
- **Donut Chart** – Revenue % by pizza size and category  

---

## 🔥 Key Insights  
- 📅 **Friday** → Highest number of orders  
- 📆 **July** → Highest revenue month (likely seasonal demand)  
- 💲 **Average Order Value** ≈ $38.5 per order  
- 🍕 **Classic pizzas** → Contributed the most revenue  
- 📏 **Large pizzas** were most preferred, **XX-Large pizzas** performed worst  
- 🥇 **Thai Chicken Pizza** → Highest revenue contributor  
- ❌ **Brie Carre Pizza** → Lowest sales & revenue contributor  

---

## ✅ Business Recommendations (Optimization)  
- Stop production of **XX-Large pizzas** → high cost, low revenue  
- Enhance promotions & taste quality for **Saturday sales boost**  
- Provide **discounts in October** (low-revenue month) to drive demand  
- Improve **chicken pizzas quality** & target **Sunday promotions**  
- Discontinue **Brie Carre Pizza** → consistently underperforming  
- Maintain & gradually increase pricing of **Classic Deluxe Pizza** → top-selling item  

---

## 💻 Tech Stack  
- **Database**: SQL Server  
- **Visualization**: Microsoft Power BI  
- **DAX**: Custom measures for business KPIs  
- **ETL**: Power Query (data cleaning & transformation)  

---

## 👨‍💻 Author  
**Aravind Udiyana**  
📧 aravindudiyana123@gmail.com   

---
