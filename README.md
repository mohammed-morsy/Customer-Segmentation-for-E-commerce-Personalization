# Customer Segmentation Using K-Means and PCA

## Project Overview
This project applies **K-means clustering** and **Principal Component Analysis (PCA)** to segment customers based on purchasing behavior in an e-commerce dataset. The goal is to identify distinct customer groups to enable personalized marketing strategies and product recommendations.

## Dataset
- The dataset used is the **Online Retail Dataset** from the **UCI Machine Learning Repository**.
- It contains transaction data from **01/12/2010 to 09/12/2011** for a UK-based online retailer.
- Dataset link: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
- The company primarily sells unique, all-occasion gifts, with many customers being wholesalers.

## Project Steps
### **1. Data Understanding & Preparation**
- Import necessary libraries
- Load the dataset
- Data exploration: handling missing values, duplicates, and inconsistencies
- Data cleaning and transformation

### **2. Feature Engineering**
- **RFM Analysis (Recency, Frequency, Monetary Value)**
  - **Recency:** Last time a customer made a purchase
  - **Frequency:** Total number of purchases
  - **Monetary:** Total spending amount
- **Product Diversity Analysis**
- **Behavioral Features**
- **Geographic Features**
- **Cancellation Rate Calculation**
- **Seasonality & Trend Analysis**

### **3. Feature Scaling**
- Standardizing the data to ensure uniform feature scaling.

### **4. Dimensionality Reduction with PCA**
- Applying PCA to reduce feature space dimensionality while preserving key information.

### **5. Determining Optimal Number of Clusters**
- Using **the elbow method** to find the optimal number of clusters for K-means.

### **6. K-means Clustering**
- Performing K-means clustering on the reduced feature set.
- Assigning customers to specific clusters.
- Analyzing clusters to interpret customer segment characteristics.

### **7. Visualization**
- Using scatter plots to depict clusters and their separation in the feature space.

### **8. Evaluation**
- Assessing clustering quality using **Silhouette Score**.
- Understanding the cohesiveness and separation of clusters.

### **9. Cluster Profiling & Personalization Strategies**
- **Cluster Profiling:** Identifying unique characteristics of each cluster.
- **Personalized Recommendations:** Tailoring marketing strategies, promotions, and product suggestions for each customer segment.

### **10. Insights & Business Implications**
- Customer segmentation enables targeted marketing and improved engagement.
- Different customer groups require different engagement strategies.
- Identifying customers with high cancellation rates allows for proactive issue resolution.
- Growth opportunities exist in expanding beyond the UK market.
- Implementing **AI-powered recommendation systems** can enhance sales and customer retention.
- Strategies such as:
  - Increasing engagement for customers with low frequency but recent activity.
  - Offering targeted discounts for customers with limited product diversity.
  - Addressing high cancellation rates with better customer support.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas`, `numpy` (Data manipulation)
  - `matplotlib`, `seaborn`, `plotly` (Visualization)
  - `scikit-learn` (Machine Learning: PCA, K-means, Evaluation Metrics)
  - `scipy` (Statistical analysis)


## Results
- Customers are segmented into meaningful groups based on their purchasing behavior.
- Insights are generated to assist in personalized marketing and customer engagement.
- Visualizations help in understanding the distribution and separation of clusters.


## Acknowledgments
- **UCI Machine Learning Repository** for providing the dataset.
- Open-source contributors for maintaining the Python libraries used in this project.

