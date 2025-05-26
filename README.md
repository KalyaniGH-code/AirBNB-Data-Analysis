# AirBNB- Exploratory Data Analysis - Data-Analysis
## PROJECT SUMMARY
The purpose of this project is to explore and analyze Airbnb data from New York City to discover patterns related to pricing, location, availability, and customer engagement. Through EDA techniques, we aim to answer questions such as:
•	Which neighborhoods have the highest average prices?
•	How does room type affect pricing?
•	What is the distribution of availability across listings?
By leveraging libraries like Pandas, NumPy, Matplotlib, and Seaborn, we transform raw data into actionable insights.

## PROJECT OBJECTIVES:
•	Explore the distribution of room types, pricing, and availability across various neighborhoods in New York City.
•	Examine host activity and identify trends in listing behaviors.
•	Identify and investigate unusual or extreme price values that may indicate outliers.
•	Offer data-driven recommendations for both guests and hosts based on key findings from the analysis.
## STEPS INVOLVED IN ANALYSIS:-
1. Data Cleaning
•	Handled Missing Values: Addressed null values in key columns such as price, neighbourhood, latitude, longitude, room_type, minimum_nights, number_of_reviews, last_review, reviews_per_month, calculated_host_listings_count, availability_365 and number_of_reviews_ltm.
•	Removed Outliers: Capped listings with prices  $1,500 to reduce skewness in visualizations and analysis.
2. Exploratory Data Analysis (EDA)
   --- Room Type Distribution
•	Used bar plots to visualize the frequency of each room type.
•	Found that "Entire home/apt" is the most common accommodation type.
   --- Neighborhood Group Insights
•	Explored average prices across different boroughs.
•	Identified Manhattan as having the highest average listing prices.
   Availability Trends
•	Created heatmaps to analyze relationships among price, availability_365, number_of_reviews, and beds.
  --- Price Distribution
•	Used histograms to examine how listing prices are distributed.
•	Observed that most listings fall in the $50–$300 range.
   --- Host Listings
•	Analyzed hosts with multiple listings using boxplots to identify high-activity hosts.
   --- REVIEW
•	Used pair plots to explore interactions between number_of_reviews, price, and availability.
3. Data Visualization Techniques
•	Pair Plots: Explored relationships among price, availability, and number_of_reviews.
•	Heatmaps: Displayed correlation between numerical variables.
•	Histograms & Boxplots: Identified outliers and distribution patterns in listing prices.
•	Bar Charts: Showed the distribution of room types and neighborhood groups.
## CONCLUSION
•	This project provides meaningful insights into the New York City Airbnb market, enabling both guests and hosts to make more informed decisions. Through Exploratory Data Analysis (EDA), we uncovered important trends in pricing, availability, room types, and host behavior. These insights led to actionable recommendations aimed at improving user experience and market understanding.

