# ☕ Coffee Sales Analysis & Forecasting Dashboard | Excel Project

## 📌 Project Overview
This project focuses on analyzing coffee sales in Saudi Arabia over a two-year period using Microsoft Excel, Power Pivot, and Power Query. The dataset contains sales records for 100 customers and 5 different coffee bean types. The goal is to uncover insights that help businesses make data-driven decisions on sales strategy, inventory planning, and marketing focus.

---

## 📅 Dataset Information
- **Source:** Kaggle (Synthetic dataset)
- **Duration:** January 1, 2023 – December 31, 2024
- **Region:** Saudi Arabia
- **Products:** Brazilian, Ethiopian, Colombian, Costa Rica, Guatemala coffee beans

### 🔢 Columns:
- `Date`: Purchase date  
- `Customer_ID`: Unique customer ID  
- `Category`: Product category (Coffee Beans)  
- `Product`: Type of coffee  
- `Unit Price`: Price per unit  
- `Quantity`: Units purchased  
- `Sales Amount`: Quantity × Unit Price  
- `Used_Discount`: Whether a discount was applied (True/False)  
- `Discount_Amount`: 20% value  
- `Final Sales`: Sales after discount

---

## 🧹 Data Cleaning & Preparation
- Reviewed dataset and understood column meanings  
- Extracted `Day` and `Month` from the `Date` column for time-based analysis  
- Converted `Customer_ID` to text format to avoid calculation issues  
- Standardized formatting for readability  
- Built a proper **Data Model** using Power Pivot for relational analysis

---

## 📊 Key Analyses Performed
1. Daily and monthly sales trends  
2. Top 3 cities by total sales  
3. Top 3 coffee products by sales  
4. Discount effectiveness analysis  
5. Total sales overview  
6. Sales forecasting sheet with confidence intervals

---

## 📈 Key Insights
- **Mondays and Fridays** had the highest sales volume  
- **Monthly sales** remained consistent throughout the year  
- Cities like **Hail** and **Jeddah** led in total purchases  
- **Colombian coffee** was the top-selling product, though all types performed well  
- **Discounts** had no significant impact on customer purchase behavior

---

## 🔮 Forecasting Sheet
A forecasting model was created to project future sales based on historical data. The central line in the forecast represents expected future values, while the upper and lower boundaries reflect confidence intervals.

**Recommendation:** Use the forecast to plan stock levels and adjust operations based on expected demand fluctuations.

---

## 📌 Tools & Features Used
- Excel  
- Power Pivot  
- Power Query  
- Pivot Tables  
- Slicers  
- Forecasting Sheet  
- Interactive Dashboard

---

## ✅ Outcome
This project demonstrates how Excel can be used to transform raw sales data into actionable business intelligence. The interactive dashboard and forecasting help support strategic decision-making in marketing, inventory, and operations.
