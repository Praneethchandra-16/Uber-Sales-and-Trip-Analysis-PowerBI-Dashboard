# Uber Trip Analysis Dashboard (Power BI)

## Project Overview
This project analyzes Uber trip data using Power BI to uncover booking trends, revenue insights, and trip efficiency.  
The interactive dashboards provide stakeholders with a clear view of customer behavior, operational efficiency, and revenue generation.

---

## Dataset
- Trip Details Table: Includes pickup/drop-off times, passenger count, trip distance, fare amount, payment type, surge fees, and vehicle type.  
- Location Table: Maps numeric `LocationID` values to actual area names.  
- Calendar Table: Created to enable time-based analysis (day, date, weekday).  

---

## Dashboards

### 1. Overview Analysis
- KPIs: Total Bookings, Total Booking Value, Average Booking Value, Total Trip Distance, Average Trip Distance, Average Trip Time  
- Bookings by Payment Type (Card, Cash, Wallet, etc.)  
- Bookings by Trip Type (Day vs. Night)  
- Vehicle type performance (Matrix with KPIs and conditional formatting)  
- Top 5 locations with the highest bookings  
- Most frequent pickup and drop-off points  
- Farthest trip details  

### 2. Time Analysis
- Bookings across 10-minute pickup intervals (Area Chart)  
- Weekly booking patterns (Line Chart)  
- Heatmap showing bookings by hour of the day × day of the week  
- Dynamic KPI selector to switch between Bookings, Revenue, and Distance  

### 3. Details Tab
- Grid table with detailed trip-level data (Trip ID, Distance, Value, Locations, Payment Type, etc.)  
- Drill-through functionality from other dashboards for deeper exploration  
- Bookmarks to toggle between filtered and full dataset views  

---

## Features Implemented
- Dynamic Measures using a disconnected table and DAX SWITCH  
- Day/Night Trip Classification based on pickup time  
- Inactive Relationship Handling with USERELATIONSHIP for drop-off analysis  
- Dynamic Titles to update visuals based on selected KPI  
- Bookmarks for Data Details and Full Dataset view  
- Export Option for raw data download  

---

## Key Insights
- Peak bookings observed during weekday mornings and weekend evenings  
- Card payments dominate, but cash usage remains significant in some areas  
- Short-distance trips are more frequent, but long-distance trips generate higher fares  
- Certain pickup and drop-off locations consistently account for the majority of bookings  
- Vehicle preferences vary by location, indicating opportunities for optimized vehicle allocation  

---

## How to Use
1. Clone this repository.  
2. Open the `.pbix` file in Power BI Desktop.  
3. Connect the provided dataset (`Uber Trip Details.xlsx`).  
4. Explore the interactive dashboards.  

---

## Screenshots 
- Overview Dashboard  
- Time Analysis Dashboard  
- Details Tab  

---

## Conclusion
The Uber Trip Analysis Dashboard demonstrates how transactional ride data can be transformed into actionable insights.  
It supports better decision-making in areas such as pricing strategy, resource allocation, and customer experience optimization.

---

## Contact
Developed by **Praneeth Chandra Budala**  
Connect with me on [LinkedIn](https://www.linkedin.com/in/praneeth-chandra-budala-6795b8214)  
Explore more projects on [GitHub](https://github.com/Praneethchandra-16)
# Uber-Sales-and-Trip-Analysis-PowerBI-Dashboard
