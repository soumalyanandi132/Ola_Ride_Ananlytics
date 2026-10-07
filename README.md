# Ola Ride Analytics Dashboard

A beginner-friendly Business/Data Analyst portfolio project using **Excel, SQL and Power BI** to analyze ride bookings, booking value, cancellations, vehicle performance, payment methods and customer/driver ratings.

## Business Objective
The dashboard helps a ride-hailing operations team answer five simple questions:
1. How many rides are booked and completed?
2. What is the total booking value?
3. Why are rides cancelled?
4. Which vehicle types perform best?
5. How are customers and drivers rating completed rides?

## Dataset
`data/ola_rides.csv` contains 3,000 synthetic ride-booking records. The data is created only for portfolio practice and is **not official Ola data**.

Main fields include booking ID, date/time, customer ID, vehicle type, pickup/drop locations, booking status, booking value, payment method, ride distance, ratings and cancellation reason.

## Dashboard Pages
### 1. Overview
Total bookings, completed rides, total booking value, cancellation rate, booking trend and booking-status split.

### 2. Vehicle Analysis
Bookings, booking value and average ride distance by vehicle type.

### 3. Cancellation Analysis
Customer/driver cancellations and the most frequent cancellation reasons.

### 4. Revenue & Ratings
Booking value by payment method plus average driver and customer ratings.

## Files
- `Ola_Ride_Analytics.xlsx` — cleaned dataset, KPI dashboard and Power BI build guide
- `data/ola_rides.csv` — Power BI-ready dataset
- `sql/analysis.sql` — six straightforward SQL queries
- `powerbi/DAX_Measures.txt` — measures to create in Power BI
- `docs/Interview_Explanation.md` — simple project explanation for interviews

## Tools
**Excel | SQL | Power BI**

## Note
This is an educational portfolio project inspired by ride-hailing business operations. It is not affiliated with or based on proprietary data from Ola.
