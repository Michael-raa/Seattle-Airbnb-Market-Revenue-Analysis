# 📊 Seattle Airbnb Market & Revenue Analysis (Tableau)

## 🔗 Live Interactive Dashboard
[👉 **[View Interactive Dashboard on Tableau Public](YOUR_TABLEAU_PUBLIC_LINK_HERE)**](https://public.tableau.com/app/profile/michael.raafat/viz/AirBnBFullProject_17556192976290/Dashboard1)

---

## 📌 Project Overview
This project analyzes the Seattle Airbnb market to evaluate pricing trends, revenue seasonality across 2016, and property distribution across zipcodes. The goal is to provide actionable insights for property hosts and real estate investors looking to optimize pricing strategies.

## 🔑 Key Business Insights
* **Location Pricing:** Zipcodes such as `98134` and `98101` (Downtown/Industrial area) command the highest average prices per night.
* **Seasonality Trends:** Weekly revenue peaks significantly during summer months (June–August 2016) before tapering off in Q4.
* **Bedroom Scale:** Average price increases steadily with bedroom count, with 5 and 6-bedroom properties showing the highest revenue density per listing.

## 🛠️ Data Architecture & Modeling
* **Data Sources:** `Listings` (3,800+ rows) and `Calendar` (10,000+ availability records).
* **Data Model:** Inner join on `Listings.id = Calendar.listing_id`.
* **Calculated Metrics:** Weekly Truncated Date aggregations, Average Price per Zipcode, Count Distinct (`CNTD`) Listing IDs.

## 📱 Dashboard Features
* **Interactive Filtering:** Cross-highlighting across filled geographic maps and bar charts via Zipcode actions.
* **Responsive Layout:** Includes custom desktop and mobile (Phone) layouts.

---
### 🖼️ Dashboard Preview
<img width="1340" height="543" alt="Screenshot 2026-09-24 041445" src="https://github.com/user-attachments/assets/5ba4a761-b34e-45ee-84a8-5340108d7363" />
