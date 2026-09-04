Global Airbnb Performance Dashboard
A dynamic, interactive data visualization report designed to analyze Airbnb listing trends, market distribution, pricing dynamics, seasonality, host trust signals, and customer ratings across major global cities.

Headline:
Global Airbnb Performance Dashboard
An interactive Power BI report for evaluating market share, host verification metrics, pricing competitiveness against hotels, review seasonality, and granular city-level satisfaction scores.

Purpose:
The Global Airbnb Performance Dashboard provides a comprehensive macro and micro analysis of 279,712 listings across 10 global cities and 182,024 hosts. Designed for hospitality analysts, real estate investors, and strategy consultants, this dashboard tracks growth trajectories, pricing models, listing distribution, and guest sentiment to inform host optimization and market entry strategies.

Tech Stack:
Power BI Desktop – Core data visualization platform used for dashboard assembly, dynamic view switching, and layout design.
Power Query – Data cleaning, transformation, and reshaping layer for raw listing, review, and host dataset ingestion.
DAX (Data Analysis Expressions) – Used for calculated measures, market share percentages, dynamic rating toggles, and cumulative distribution curves.
Data Modelling with cross filter direction set as both


Data Source: Maven Analytics
(https://mavenanalytics.io/data-playground/airbnb-listings-reviews)
* **Data Volume:** 182,024 unique hosts, 144 property types, and over 5.37 Million (5,373K) guest reviews from 2008 through 2020.

Features / Highlights

### Business Problem
The global short-term rental market requires continuous benchmarking against traditional lodging options (hotels) and local regulatory frameworks. Property managers and investors face critical questions such as:
* Which global markets hold the largest listing share, and where are market saturated?
* How do listing growth trends align with external shocks (e.g., local regulatory shifts or global pandemics like COVID-19)?
* Does host profile verification directly correlate with review activity and guest trust?
* Which specific service metrics (Cleanliness, Accuracy, Value) drive overall city satisfaction scores?

### Goal of the Dashboard
To provide a single interactive interface that allows users to monitor historical listing growth, compare host trust signals, evaluate pricing variations across room types, and dissect customer satisfaction across specific operational dimensions.

### Walkthrough of Key Visuals
* **KPI Metrics Ribbon:** Displays high-level summaries for total listings (279.7K), total cities (10), unique hosts (182K), distinct property types (144), and total reviews (5.37M).
* **New Listings Growth Curve (2008–2020):** Area and line combination chart mapping listing adoption phases (Take-off point in 2010, Peak in 2015, Regulatory restraint in 2016–2017, and COVID-19 decline in 2020) segmented by room type.
* **Market Share & Concentration Curve:** Pareto-style combination chart highlighting market share by city, where Paris, NYC, and Sydney account for nearly 48% of total listings.
* **Average Price Comparison Bar Chart:** Horizontal bar chart displaying price differentials across lodging types (Hotel Room: ~$800, Entire Place: ~$673, Shared Room: ~$580, Private Room: ~$462).
* **Seasonality Ribon:** Monthly review distribution showing European summer peak travel (Paris & Rome dominating April–August) vs. holiday season surges (New York peaking in November–December).
* **Trust & Verification Matrix:** Shield visual analyzing host profile verification rates (66.9% fully verified with profile picture vs. 0.3% unverified without picture).
* **Interactive Rating View (Dynamic Toggle):** 
  * *Overall Rating View:* Column chart ranking cities by average rating (Mexico City leading at 94.8, Hong Kong lowest at 89.7).
  * *Detailed View:* Heatmap table breaking down scores across 5 specific metrics: Accuracy, Cleanliness, Communication, Location, and Value.

### Business Impact & Insights
* **Market Expansion Strategy:** Real estate operators can target high-performing, high-satisfaction regions like Mexico City and Rio de Janeiro while identifying underperforming service areas in Hong Kong and Istanbul.
* **Pricing Optimization:** Highlights competitive advantages where hotel room prices average nearly double ($800) compared to alternative Airbnb lodging options.
* **Quality & Trust Standards:** Demonstrates that over two-thirds of hosts maintain complete verification signals, reinforcing platform security and booking conversion.
* **Operational Focus:** Heatmap breakdown identifies Cleanliness and Value-for-Money as the primary drivers holding down overall ratings across low-performing cities.

## 6. Screenshots / Demos

*(https://github.com/DebankurChakraborty2003/Airbnb-Dashboard/blob/main/Airbnb%20Dashboard%20Overview.png)*
*(https://github.com/DebankurChakraborty2003/Airbnb-Dashboard/blob/main/Airbnb%20Dashboard%20Overall%20Rating%20View.png)*
*(https://github.com/DebankurChakraborty2003/Airbnb-Dashboard/blob/main/Airbnb%20Dashboard%20Detailed%20Rating%20View.png)*
*(https://github.com/DebankurChakraborty2003/Airbnb-Dashboard/blob/main/Airbnb%20Dashboard%20Review.png)*
