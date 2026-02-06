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


---

# 2. Amazon Prime Video Analysis – Tableau Project

## 📊 Project Overview
This project analyzes Amazon Prime Video content data to understand the platform’s content distribution, genre availability, release trends, and rating patterns.  
The goal of the analysis is to provide insights into how Amazon Prime structures its content library across different countries, years, and content types.

An interactive Tableau dashboard was created to visualize content trends and support data-driven insights.

---

## 🎯 Objectives
- Analyze Movies vs TV Shows distribution
- Understand content availability by country
- Study genre-wise content distribution
- Analyze release year trends
- Explore rating patterns across content types
- Present insights using interactive Tableau dashboards

---

## 🧹 Data Cleaning & Preparation
The following data preparation steps were performed:
- Cleaned and standardized release year values
- Handled NULL values in country, rating, and genre fields
- Split and grouped multiple genre values for analysis
- Created calculated fields for:
  - Total Titles
  - Content Type (Movie / TV Show)
  - Release Year Trends
- Ensured consistent formatting for dashboard visuals

---

## 📈 Dashboard Components

### 🎬 Movies vs TV Shows
Displays the distribution of Movies and TV Shows available on Amazon Prime.

---

### 🌍 Content by Country
Shows content availability across different countries to identify regional coverage.

---

### 🗂 Genre Distribution
Analyzes the most common genres available on the platform.

---

### 📅 Release Year Trend
Shows how content production has changed over time based on release years.

---

### ⭐ Rating Analysis
Displays content distribution across different ratings.

---

## 🔍 Key Insights
- Movies form the majority of content on Amazon Prime
- Content availability is higher in specific regions
- Certain genres dominate the content library
- Significant growth in content after recent years
- Rating distribution varies between Movies and TV Shows

---

## ⚠️ Data Limitations
- Dataset does not include viewership or user engagement data
- No financial or subscription revenue information available
- Genre and country fields may contain multiple values per title

---

## 🛠 Tools Used
- Tableau
- Data Visualization
- Calculated Fields
- Exploratory Data Analysis (EDA)

---

## 👤 Author
**Justin Joji**  
Data Analyst | Tableau | Power BI  

---

## 📌 Note
This project is created for learning, portfolio development, and interview demonstration purposes.
