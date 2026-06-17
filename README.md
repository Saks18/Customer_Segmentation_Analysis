# Customer Segmentation Analysis

## Project Overview

Customer Segmentation Analysis is a data analytics project that uses Machine Learning and Business Intelligence techniques to identify distinct customer groups based on their purchasing behavior and demographics.

The project analyzes customer data from a shopping mall and applies K-Means Clustering to segment customers into meaningful groups. These insights can help businesses create targeted marketing campaigns, improve customer retention, and optimize resource allocation.

---

## Business Problem

Businesses often struggle to understand the diverse needs and behaviors of their customers. Treating all customers the same can lead to ineffective marketing strategies and lower customer satisfaction.

This project aims to answer:

* Who are the most valuable customers?
* Which customers have high spending potential?
* How can businesses target different customer groups effectively?
* What marketing strategies can be designed for each segment?

---

## Dataset

The dataset contains customer information collected from a shopping mall.

### Features

| Feature                | Description                               |
| ---------------------- | ----------------------------------------- |
| CustomerID             | Unique customer identifier                |
| Gender                 | Customer gender                           |
| Age                    | Customer age                              |
| Annual Income (k$)     | Annual income in thousand dollars         |
| Spending Score (1-100) | Score assigned based on spending behavior |

---

## Project Workflow

### 1. Data Collection

* Imported customer dataset
* Checked data quality and structure

### 2. Data Cleaning

* Handled missing values
* Verified data consistency
* Removed unnecessary columns

### 3. Exploratory Data Analysis (EDA)

* Customer demographics analysis
* Income distribution analysis
* Spending score analysis
* Gender-based comparisons
* Correlation analysis

### 4. Customer Segmentation

* Applied K-Means Clustering
* Used the Elbow Method to determine the optimal number of clusters
* Segmented customers based on income and spending patterns

### 5. Data Visualization

* Cluster visualization
* Customer distribution charts
* Income vs Spending Score analysis

### 6. Dashboard Development

* Built an interactive Power BI dashboard
* Visualized customer insights and segment distribution

---

## Technologies Used

### Programming & Analytics

* Python
* Jupyter Notebook

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Business Intelligence

* Power BI

---

## Machine Learning Technique

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to group similar customers based on their characteristics.

The algorithm:

1. Selects cluster centroids
2. Assigns customers to the nearest centroid
3. Recalculates centroid positions
4. Repeats until convergence

The Elbow Method was used to determine the optimal number of customer segments.

---

## Key Insights

### High Income – High Spending Customers

* Most valuable customer segment
* Ideal target for premium products and loyalty programs

### High Income – Low Spending Customers

* Significant purchasing potential
* Opportunity for personalized marketing campaigns

### Low Income – High Spending Customers

* Frequent spenders despite lower income
* Responsive to discounts and promotional offers

### Low Income – Low Spending Customers

* Lower engagement segment
* Suitable for mass-market campaigns

### Average Income – Average Spending Customers

* Stable customer base
* Important for long-term retention strategies

---

## Dashboard Features

The Power BI dashboard provides:

* Customer demographics overview
* Income analysis
* Spending behavior analysis
* Cluster distribution
* Interactive filtering
* Business insights visualization

---

## Author

### Sakshi Borkar

Aspiring Data Analyst | Business Analyst | Marketing Analytics Enthusiast

Skills:

* Python
* SQL
* Power BI
* Data Analytics
* Machine Learning
* Marketing Analytics

GitHub: https://github.com/Saks18

---

## Conclusion

This project demonstrates how machine learning and data analytics can be used to transform raw customer data into actionable business insights. By identifying distinct customer segments, organizations can make data-driven decisions, improve marketing effectiveness, and enhance customer satisfaction.
