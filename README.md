# Analyzing Customer Patterns for Retail Stores

**Introduction:**

Retail stores constantly aim to understand customer behavior to optimize their services, increase sales, and enhance customer satisfaction. This project analyzes shopping behavior using machine learning techniques to uncover patterns in customer purchasing habits. By leveraging advanced visualization and clustering methods, this analysis provides actionable insights for improving decision-making in retail.

**Files in Repository:**

• analyzing_customer_patterns.ipynb - Contains the Jupyter Notebook with code implementation.

• shopping_behavior_updated (1).csv - Dataset used for analysis.

**Problem Statement:**

Retailers struggle to identify customer patterns due to vast data and complex behaviors. This project analyzes purchasing trends, segments customers, and provides insights to optimize inventory and personalize marketing strategies.

**Dataset Overview:**

The dataset used in this project provides a comprehensive view of customer behavior and purchasing patterns. It comprises diverse features that can be categorized into the following sections:

• Demographics: Age, Gender, Location

• Purchase Details: Item Purchased, Category, Size, Color, Purchase Amount

• Transaction Details: Payment Method, Frequency of Purchases, Subscription Status

• Contextual Information: Season, Review Rating, Discount Applied, Promo Code Used, Shipping Type

**Methodology:**

1. Data Preprocessing
   
   • Inspected data structure (info, shape, columns, and head functions)

   • Dropped irrelevant columns (e.g., Customer ID)

   • Identified and separated numerical and categorical columns

2. Data Exploration

   • Analyzed data distributions and unique values

   • Visualized trends using bar plots, pie charts, and scatter plots

3. Visualization

   • Utilized Plotly Express for interactive visualizations
   
   • Highlighted trends in categories like product types, seasons, locations, and payment methods

4. Clustering

   • Standardized numerical data using StandardScaler

   • Applied KMeans Clustering to group customers into 3 distinct segments

   • Visualized clusters based on the first two numerical features

**Implementation:**

**Step 1: Data Preprocessing**

• Removed the Customer ID column

• Identified and separated 7 numerical columns and 10 categorical columns

• Checked for null values and duplicates to ensure data integrity

**Step 2: Exploratory Data Analysis**

• Bar and Pie Charts: Visualized distributions of categorical columns such as Category, Size, Season, etc.

  Example: Winter purchases dominated by items like coats and sweaters

• Numerical Analysis: Examined variables such as Purchase Amount and Review Rating

Step 3: Clustering for Segmentation

• Used StandardScaler to normalize numerical columns for K-Means clustering

• Chose 3 clusters to represent distinct customer segments:

a. Cluster 0: High-frequency buyers with high average purchase amounts

b. Cluster 1: Seasonal shoppers purchasing during promotions

c. Cluster 2: Budget-conscious buyers prioritizing discounts

• Visualized clusters with scatter plots to identify relationships between variables

Step 4: Cluster Centers

• Extracted cluster centers representing the average profile of each segment:
  
  Example: Cluster 0 prefers express shipping and higher-priced items

**Conclusion:**

The analysis reveals distinct customer segments, each with unique preferences, providing valuable insights for retail stores. By understanding these segments, stores can:

• Optimize inventory to ensure high-demand products are available during peak seasons

• Personalize marketing strategies for targeted campaigns

• Enhance customer satisfaction by tailoring shipping and payment options

This approach ultimately helps retail stores boost efficiency, improve customer loyalty, and increase sales.
