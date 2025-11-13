# 🍕 **Pizza Sales Analytics Dashboard (SQL + MS EXCEL)**  

## **📌 Project Objective**  
The goal of this project is to analyze pizza sales data to understand revenue trends, customer behaviour, and product-level performance.  
The insights support business decisions related to menu optimization, staffing, and inventory planning.

---

## **📁 Dataset Used**  
The dataset includes:  
- Order details  
- Order date and time  
- Pizza names  
- Pizza categories  
- Pizza sizes  
- Quantity sold  
- Total price  

---

## **📊 KPIs / Business Questions**  
1. Total Revenue  
2. Total Orders  
3. Average Order Value (AOV)  
4. Total Pizzas Sold  
5. Average Pizzas per Order  
6. Daily Trend of Orders  
7. Hourly Trend of Orders  
8. Sales by Pizza Category  
9. Sales by Pizza Size  
10. Top 5 Best Selling Pizzas  
11. Bottom 5 Worst Selling Pizzas  

---

## **🧹 Data Cleaning & Preparation (SQL)**  
- Removed duplicate order IDs  
- Standardized date and time fields  
- Cleaned category and size labels  
- Verified price and quantity consistency  
- Handled missing or null values  
- Ensured each order_id mapped correctly to total_price  

---

## **🛠 SQL Techniques Applied**  
- `SUM()` for revenue and quantity  
- `COUNT()` and `COUNT(DISTINCT)` for order counts  
- `GROUP BY` for category-wise and time-wise summaries  
- `DATEPART()` and `DATENAME()` for hour/day trends  
- `ORDER BY` with `TOP` for identifying best and worst sellers  

---

## **📈 Key Insights**  
- Medium and large pizzas drive the highest revenue  
- Sales peak during lunch and dinner hours  
- Classic and Supreme categories dominate order volume  
- A small group of pizzas contribute a major share of revenue  
- Several items consistently underperform and may require menu review  

---

## **📂 Final Dashboard Output**  
The final dashboard includes:  
- KPI Cards  
- Daily and Hourly Order Trends  
- Category & Size-wise Sales Distribution  
- Top 5 Bestsellers  
- Bottom 5 Worst Sellers  
- Interactive slicers for deeper analysis  

---

## **📌 Tools Used**  
- SQL   
- Excel  

---

## **⭐ Project Outcome**  
The dashboard provides a complete understanding of:  
- Customer demand patterns  
- Product performance  
- Revenue contribution  
- Operational improvement opportunities  

