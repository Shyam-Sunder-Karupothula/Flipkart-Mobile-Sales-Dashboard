📊 Flipkart Mobile Sales Dashboard
This project focuses on extracting, analyzing, and visualizing smartphone sales data from Flipkart to uncover pricing patterns, brand performance, and technical specification trends. The goal is to support data-driven business decisions in e-commerce and electronics retail domains.

📌 Project Description
Using data scraped from Flipkart (via BeautifulSoup/Selenium), I compiled key product information such as price, reviews, RAM/ROM configurations, display sizes, processors, and ratings for 120 smartphones across 16 brands.

The cleaned dataset was then imported into Power BI where a fully interactive dashboard was built to track pricing strategies, customer preferences, and specification-wise trends.

🎯 Business Purpose
This dashboard serves as a decision-support tool for:

Retail strategy teams to identify best-selling brands and specifications.

Product managers to optimize product portfolios based on performance and price segmentation.

Marketing teams to understand what drives reviews and ratings.

Data analysts to monitor trends and generate insights without manual tracking.

🔍 Key Insights from the Dashboard
Apple has the highest average pricing (~₹49K) but lower total reviews, indicating a premium market segment with less volume.

Vivo leads in customer engagement with 108 reviews, making it a key brand to monitor for volume strategy.

8GB–12GB RAM models capture the highest revenue share, implying mid to high-spec phones are most profitable.

Snapdragon processors dominate in terms of cumulative sales value (~₹1.6M), followed by generic or less branded chips.

Most popular screen sizes are between 6.0" and 6.8", which helps in understanding consumer form-factor preferences.

Despite Apple having 0 RAM listing (displayed as 'Not Available'), it still competes in high price brackets—handled with a custom label to improve clarity in visuals.

🧠 How This Helps Business Strategy
Area	Dashboard Impact
Product Pricing	Reveals how specs (RAM, Display, Processor) affect total price contribution.
Brand Monitoring	Tracks top-performing brands by reviews, price, and product count.
Customer Insights	Displays which brands/specs attract more reviews and higher ratings.
Inventory Planning	Helps focus stock and procurement around popular specs like 8GB RAM or Snapdragon SoCs.
Marketing Campaigns	Target campaigns around price tiers and high-engagement devices.

⚙️ Tools Used
Python (BeautifulSoup, Selenium): For web scraping mobile product data.

Excel / Power Query: For data cleaning and transformation.

Power BI: For building the visual dashboard.

DAX (Data Analysis Expressions): For KPIs like Avg Price, Avg Ratings, Top Brands by Reviews.

