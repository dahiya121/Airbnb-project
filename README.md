# Airbnb Dashboard 🏡📊

An interactive Power BI dashboard project designed to analyze Airbnb listings data from **Chicago** and **New Orleans**, delivering rich insights into revenue, pricing, host performance, and neighborhood-level trends.

---

## 📌 Project Overview

This dashboard provides actionable insights for property owners, analysts, and investors by visualizing key business metrics derived from Airbnb data. It allows dynamic filtering by city, room type, and time period to support deeper market understanding and smarter decisions.

---

## 🚀 Features

- **Total Revenue**: Aggregated across bookings
- **Bookings & Hosts**: Track volume of listings and active hosts
- **Revenue per Booking & Room Type**
- **Yearly Revenue Trend** with interactive line chart
- **Average Price Gauge**
- **Max Price by Room Type**
- **Top Hosts by Review Count**
- **Reviews by Year and Month**
- **Neighborhood-wise Price Analysis**
- **Geospatial Mapping** using Bing Maps
- **Dynamic Filtering** by:
  - 📍 City
  - 🏘️ Room Type
  - 📅 Year Range

---

## 🧮 DAX Logic Used

To calculate total revenue (approximation based on available fields):

dax
Total Revenue = SUMX('Table', 'Table'[price] * 'Table'[minimum_nights] * 'Table'[number_of_reviews])

## Connect With me  Email- dhaiyapraveen4@gmail.com
##               Linkdin- www.linkedin.com/in/praveen-dahiya01      


