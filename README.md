# Customer Segmentation using K-Means Clustering

## Project Overview

This project focuses on customer segmentation using the K-Means Clustering algorithm. The objective is to group customers with similar purchasing behavior into distinct segments based on their annual income and spending patterns.

Customer segmentation helps businesses understand different customer groups and create targeted marketing strategies to improve customer engagement, retention, and sales.

---

## Dataset

Dataset Used: Mall Customers Dataset

Features available in the dataset:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, the following features were used:

- Annual Income (k$)
- Spending Score (1-100)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```bash
Syntecxhub_Customer_Segmentation/
│
├── Mall_Customers.csv
├── Customer_Segmentation.ipynb
├── customer_clusters.csv
└── README.md
```

---

## Project Workflow

### 1. Data Loading

Loaded the Mall Customers dataset and explored its structure.

### 2. Data Cleaning

- Checked dataset information
- Verified data types
- Checked for missing values
- Performed basic preprocessing

### 3. Exploratory Data Analysis (EDA)

Analyzed customer characteristics using:

- Gender Distribution
- Age Distribution
- Spending Score Distribution

### 4. Feature Selection

Selected the following features for clustering:

- Annual Income (k$)
- Spending Score (1-100)

### 5. Feature Scaling

Applied StandardScaler to normalize feature values before clustering.

### 6. Elbow Method

Used the Elbow Method to determine the optimal number of clusters (K).

### 7. K-Means Clustering

Applied K-Means Clustering to group customers into segments based on spending behavior and income levels.

### 8. Cluster Visualization

Visualized customer clusters using scatter plots to understand segment separation.

### 9. Cluster Profiling

Calculated average values of:

- Age
- Annual Income
- Spending Score

for each cluster to understand customer characteristics.

### 10. Export Results

Saved the final dataset with assigned cluster labels as:

```text
customer_clusters.csv
```

---

## Cluster Analysis

The generated customer segments help identify different customer groups such as:

### High Income – High Spending Customers

Characteristics:
- Premium customers
- High purchasing power
- Frequent buyers

Marketing Actions:
- Loyalty programs
- VIP memberships
- Exclusive offers

### High Income – Low Spending Customers

Characteristics:
- Strong purchasing power
- Lower engagement

Marketing Actions:
- Personalized recommendations
- Cross-selling campaigns
- Targeted promotions

### Low Income – High Spending Customers

Characteristics:
- Active shoppers
- Price-sensitive customers

Marketing Actions:
- Discounts
- Reward points
- Seasonal offers

### Low Income – Low Spending Customers

Characteristics:
- Occasional shoppers
- Limited purchasing activity

Marketing Actions:
- Budget-friendly promotions
- Awareness campaigns

### Moderate Income – Moderate Spending Customers

Characteristics:
- Balanced purchasing behavior

Marketing Actions:
- Retention strategies
- Personalized marketing

---

## Visualizations Included

The notebook contains:

- Gender Distribution Plot
- Age Distribution Histogram
- Spending Score Distribution Histogram
- Elbow Method Plot
- Customer Segmentation Scatter Plot

---

## Output Files

### customer_clusters.csv

Contains:

- Original customer data
- Assigned cluster label for each customer

---

## How to Run

### Clone the Repository

```bash
git clone <https://github.com/Dikshitha-Reddy-Vanga/Syntecxhub_Customer_Segmentation>
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Customer_Segmentation.ipynb
```

Run all cells sequentially.

---

## Learning Outcomes

This project demonstrates:

- Unsupervised Machine Learning
- Customer Analytics
- Feature Scaling
- K-Means Clustering
- Elbow Method
- Cluster Visualization
- Business-Oriented Data Interpretation

---

## Future Improvements

Possible enhancements include:

- Hierarchical Clustering
- DBSCAN Clustering
- RFM Analysis
- Interactive Dashboard using Power BI or Tableau
- Customer Recommendation System

---

## Conclusion

This project successfully segments customers into meaningful groups using K-Means Clustering. By analyzing spending behavior and annual income, businesses can better understand their customers and implement targeted marketing strategies to improve customer satisfaction and business performance.

---

## Author

Dikshitha Reddy Vanga
