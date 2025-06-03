# 📊 Flipkart Mobile Sales Dashboard

This project focuses on extracting, analyzing, and visualizing smartphone sales data from Flipkart to uncover pricing patterns, brand performance, and technical specification trends. The goal is to support data-driven business decisions in e-commerce and electronics retail domains.

---

## 📌 Project Description

Using data scraped from Flipkart (via **BeautifulSoup** and **requests**), I compiled key product information such as:

- Price  
- Reviews  
- RAM/ROM configurations  
- Display sizes  
- Processor types  
- Ratings  

The final dataset includes **120 smartphones across 16 brands**. After cleaning and transforming the data in **Excel**, I used **Power BI** to build a fully interactive dashboard that helps track pricing strategies, customer preferences, and technical trends.

---

## 🎯 Business Purpose

This dashboard serves as a decision-support tool for:

-  **Retail strategy teams** to identify best-selling brands and specifications.
-  **Product managers** to optimize product portfolios based on performance and pricing.
-  **Marketing teams** to understand what drives reviews and ratings.
-  **Data analysts** to monitor trends and generate insights without manual tracking.

---

## 🔍 Key Insights from the Dashboard

-  **Apple** has the highest average price (~₹49K) but lower total reviews, indicating a premium niche segment.
-  **Vivo** leads with **108 reviews**, suggesting strong customer engagement and volume-based sales.
-  **8GB–12GB RAM** models generate the highest revenue—highlighting a consumer preference for performance devices.
-  **Snapdragon processors** dominate revenue (~₹1.6M), showing a strong processor-brand impact on sales.
-  Most popular screen sizes are **6.0" to 6.8"**, which guides design and inventory strategy.
-  **Apple** phones with missing RAM values were handled using custom “Not Available” labeling to retain insights in visualizations.

---

## How This Helps Business Strategy

| Area               | Dashboard Impact                                                                 |
|--------------------|----------------------------------------------------------------------------------|
| **Product Pricing** | Shows how features like RAM, Display, and Processor influence pricing tiers.     |
| **Brand Monitoring**| Ranks brands by reviews, price, and product count to assist in market tracking. |
| **Customer Insights**| Reveals which features and brands drive user engagement.                       |
| **Inventory Planning**| Helps stock popular specs like 8GB RAM or Snapdragon efficiently.             |
| **Marketing Campaigns**| Guides campaign targeting by tier and feature-based customer interest.       |

---

## ⚙️ Tools & Technologies Used

-  **Python** – Web scraping using `BeautifulSoup` and `Selenium`
-  **Excel / Power Query** – Data cleaning and transformation
-  **Power BI** – Visual dashboard creation and DAX-based KPIs
-  **DAX (Data Analysis Expressions)** – Used to calculate:
  - Average Price
  - Top Brands by Reviews
  - Highest Rated Mobiles



