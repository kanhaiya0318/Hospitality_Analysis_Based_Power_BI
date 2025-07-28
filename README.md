# 🏨 Hospitality Analysis Dashboard (Power BI)

## 📌 Project Overview
This project focuses on **analyzing hotel performance metrics** using a Power BI dashboard. The analysis helps to understand booking patterns, revenue trends, occupancy rates, and other key KPIs for better decision-making in the hospitality industry.  
The dashboard provides interactive filters for **City** and **Room Class**, allowing detailed exploration of hotel performance across different categories.

---

## 🎯 Objectives
- Analyze **Revenue**, **RevPAR(Revenue per Available Room)**, **ADR(Average Daily Rate)**, and **Occupancy%** trends.
- Compare **weekday vs weekend** performance metrics.
- Identify **booking platform performance** based on Realisation% and ADR.
- Track revenue contribution by **hotel category** (Luxury vs Business).
- Evaluate **property-wise key metrics** including cancellations, average ratings, and realization rates.
- Provide insights into operational performance to optimize strategies.

---

## 📂 Dataset Description
The project uses five datasets to create a comprehensive analysis:

1. **`dim_dates.csv`**  
   - Contains date-related information such as day, week number, month, and whether it is a weekday or weekend.  
   - **Key Columns:** date, mmm_yy, week_no, day_type  

2. **`dim_hotels.csv`**  
   - Provides hotel-specific details including property ID, name, city, and category (Luxury/Business).  
   - **Key Columns:** property_id, property_name, city, category  

3. **`dim_rooms.csv`**  
   - Defines room details such as room ID, class, and category.  
   - **Key Columns:** room_id, room_class  

4. **`fact_aggregated_bookings.csv`**  
   - Aggregated booking data containing daily sellable room nights (DSRN), ADR, and realization %.  
   - **Key Columns:** property_id, ADR, DSRN, realization%  

5. **`fact_bookings.csv`**  
   - Detailed transactional booking data including revenue realized, booking status, platform used, and ratings.  
   - **Key Columns:** booking_id, property_id, booking_date, room_category, booking_platform, booking_status, revenue_realized  

---

## 📊 Dashboard Image
![Hospitality Analysis Dashboard](Snapshot%20of%20Dashboard.png)

---

## 🔑 Key Insights
Based on the analysis of the dashboard:

1. **Revenue & Occupancy Trends**
   - Total revenue generated: **$1.71B**
   - Average Occupancy Rate: **57.87%**  
   - Weekends show higher occupancy (62.64%) compared to weekdays (55.99%).

2. **Booking Platforms Performance**
   - Realization % is consistent across platforms (~70%).
   - ADR is slightly higher for direct bookings compared to OTA platforms.

3. **Revenue by Category**
   - Luxury hotels contribute **61.6%** of total revenue, while Business hotels contribute **38.4%**.

4. **Property-Level Insights**
   - Top revenue-generating properties are primarily located in **Mumbai and Delhi**.
   - Properties with higher realization % tend to have lower cancellation rates.

5. **Trend Analysis**
   - ADR remains stable while occupancy fluctuates weekly.
   - RevPAR shows peaks during weekends indicating better room utilization.

---

## ✅ Conclusion
This Power BI dashboard provides valuable insights into the **hospitality industry performance**, helping stakeholders to make data-driven decisions to maximize revenue and optimize occupancy rates.

