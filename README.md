**📊 Customer Segmentation Analysis Project 🚀**

**Objective:**
The goal is to analyze customer data, group customers into distinct segments based on their behavior and demographics, and provide actionable insights to improve customer retention and marketing strategies.

**Project Breakdown:**
 # 1. Data Preprocessing:
Merged multiple datasets (customers, genders, cities, transactions, branches, merchants).
Handled missing values and converted data types appropriately.
Created new features like the number of coupons burned per customer and the number of transactions.
# 2. Exploratory Data Analysis (EDA):
Customer Demographics:
Pie chart showing the distribution of customers by gender.
Bar chart displaying the distribution of customers by city.
Coupon Usage Trends:
Line chart visualizing the status of coupon transactions (claimed vs. burned) over time.
Top Performing Cities/Branches:
Bar charts showcasing cities and branches with the highest number of burned coupons.
# 3. Customer Segmentation Using K-Means Clustering:
Feature engineering to select key features for segmentation (number of transactions, burned coupons, city, and gender).
Standard scaling to normalize data.
K-Means clustering applied, with different numbers of clusters (2 to 5) evaluated using the Silhouette score.
Visualized the customer clusters using scatter plots to understand their distribution.
# 4. Segment Analysis:
Analyzed each customer segment based on the average number of transactions and burned coupons.
Provided insights and recommendations for each cluster:
Highly engaged customers: Suggested offering loyalty rewards.
Less engaged customers: Recommended increasing promotional efforts.

# Technologies Used:
Python for data analysis and clustering.
Pandas for data manipulation.
Matplotlib and Seaborn for data visualization.
Scikit-Learn for clustering and feature scaling.

**Results & Insights:**
Identified distinct customer segments based on transactional behavior.
Visualized key trends, including coupon usage and top-performing locations.
Provided personalized marketing recommendations based on customer segmentation to drive engagement and loyalty.
