# tableau-projects
Tableau dashboard for operational and analytical projects 
# 1. Uber Ride Analysis – Tableau Dashboard (2024)

## 📊 Project Overview
This project analyzes Uber ride booking data for the year 2024 to understand **operational performance, cancellations, vehicle usage, and payment flow behavior**.  
An interactive Tableau dashboard was created to present both high-level trends and detailed operational insights.

The dashboard helps identify key problem areas such as ride cancellations, payment failures, and vehicle categories contributing to operational inefficiencies.

---

## 🎯 Objectives
- Analyze completed vs incomplete rides
- Understand cancellation behavior (Customer vs Driver)
- Study vehicle type performance
- Track monthly operational performance
- Analyze payment methods and payment failures
- Identify reasons for payment not reached scenarios

---

## 🧹 Data Cleaning & Preparation
The following data cleaning methods were applied:
- Converted and standardized date fields for monthly analysis
- Handled NULL values in payment method logically (treated as payment not reached)
- Cleaned cancellation flags by replacing NULLs with 0
- Created calculated fields for business metrics such as:
  - Total Rides
  - Completed vs Incomplete Rides
  - Cancelled Rides
  - Cancellation Percentage
  - Payment Flow Status
- Validated totals across multiple charts to ensure accuracy

---

## 📈 Dashboard Components

### 🚗 Rides by Vehicle Type
Shows total rides by vehicle category such as Auto, Go Mini, Go Sedan, Bike, eBike, and Uber XL to understand demand distribution.

---

### ❌ Cancellation Type
Compares cancellations caused by **Customers vs Drivers**, highlighting that driver-side cancellations are higher.

---

### ✅ Completed vs Incomplete Rides
Displays the overall success rate of rides, clearly separating completed rides from incomplete ones.

---

### 📅 Monthly Operational Performance
Shows month-wise total ride volume to identify demand trends throughout the year.

---

### 📉 Cancellation Percentage Trend
Tracks monthly cancellation percentage, showing consistent cancellation behavior across the year.

---

### 💳 Payment Method Analysis
Analyzes ride counts across different payment methods such as UPI, Cash, Uber Wallet, Credit Card, and Debit Card.

---

### ⚠️ Payment Not Reached Breakdown
Breaks down payment failures into:
- Cancelled Rides
- Other Operational Issues
- Payment Reached

This highlights that not all payment failures are due to cancellations.

---

## 🔍 Key Insights
- Driver cancellations are higher than customer cancellations
- A significant number of rides fail before reaching the payment stage
- Auto and Mini categories dominate ride volume
- Monthly demand is stable with recurring cancellation patterns
- Payment not reached cases include both cancellations and other operational issues

---

## ⚠️ Data Limitations
- Dataset contains data for only one year
- No financial or revenue-related fields available
- Profit or loss analysis is not included
- Payment NULL values represent multiple failure scenarios

---

## 🛠 Tools Used
- Tableau (Dashboarding & Visualization)
- Calculated Fields
- Data Cleaning & Validation
- Trend Analysis

---

## 👤 Author
**Justin Joji**  
Data Analyst | Tableau | Power BI  

---

## 📌 Note
This project is part of a Tableau portfolio created for learning, analysis, and interview demonstration purposes.
