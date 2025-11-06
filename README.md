# 🏨 Hospitality Chain Analysis – AtliQ Grands

## 📘 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** and **Ad-hoc Business Insights Study** for **AtliQ Grands**, a hotel chain operating in four major Indian cities — **Delhi, Mumbai, Bangalore, and Hyderabad**.  

Despite being a well-established luxury and business hotel group, AtliQ Grands has experienced a **decline in bookings and revenue** in recent months. The goal of this project is to uncover key factors behind the drop in sales, analyze performance trends, and provide actionable insights to help the management improve occupancy and revenue.  

---

## 🎯 Business Objective
- Identify reasons behind the **decline in hotel occupancy and sales**.  
- Analyze **city-wise**, **hotel-type**, and **room-category** performance.  
- Understand customer booking patterns and **platform preferences** (online vs. offline).  
- Provide **data-driven recommendations** to improve performance and profitability.  

---

## 🧩 Dataset Information
The analysis is based on multiple CSV files that represent different aspects of the business:

| File Name | Description |
|------------|-------------|
| **dim_dates** | Contains time-related information such as date, month, week number, and day type (weekday/weekend). |
| **dim_hotels** | Details of each hotel including property ID, name, category (Luxury/Business), and city. |
| **dim_rooms** | Defines room categories – Standard, Elite, Premium, and Presidential. |
| **fact_aggregated_bookings** | Aggregated data of bookings showing successful bookings and total capacity per hotel and date. |
| **fact_bookings** | Detailed transactional booking data (booking ID, booking platform, guests, revenue, ratings, etc.). |
| **new_data_august** | Additional monthly dataset containing performance metrics such as occupancy rate (occ%). |

---

## 🏢 Hotel and Room Details

### 🏨 Hotel Categories
- **Luxury Hotels:** AtliQ Grands, AtliQ Exotica, AtliQ Blu, AtliQ Bay  
- **Business Hotels:** AtliQ City, AtliQ Palace, AtliQ Seasons  

### 🛏️ Room Categories
- Standard  
- Elite  
- Premium  
- Presidential  

### 💻 Booking Channels
- AtliQ’s official website  
- Third-party booking platforms (MakeYourTrip, LogTrip, Tripster, etc.)  
- Offline/direct bookings  

---

## ⚙️ Tech Stack & Tools
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques:** Data Cleaning, Transformation, Feature Engineering, Visualization, EDA  
- **Notebook:** `hospitality_analysis.ipynb`  

---

## 📊 Key Analysis Performed
- Combined multi-source datasets using joins and merges for unified reporting.  
- Performed **data cleaning and transformation** to fix inconsistencies and missing values.  
- Calculated key metrics like **occupancy rate**, **booking success ratio**, and **revenue per booking**.  
- Conducted **city-wise and hotel-category performance analysis**.  
- Explored **room-type performance** and customer preferences by platform.  
- Visualized trends in **occupancy, booking success, and seasonal performance** using Matplotlib and Seaborn.  

---

## 💡 Key Insights
- Luxury hotels underperformed in specific cities compared to business hotels.  
- Weekends and holidays showed higher occupancy but inconsistent across cities.  
- Bookings from **third-party platforms** dominated but with higher commission losses.  
- Underutilization of premium rooms led to reduced profitability.  
- Optimizing pricing and marketing strategy could improve overall occupancy by **12–15%**.  

---

## 📈 Results
The analysis helped uncover operational inefficiencies and provided **data-backed recommendations** for improving AtliQ’s occupancy, pricing, and booking strategy.  
