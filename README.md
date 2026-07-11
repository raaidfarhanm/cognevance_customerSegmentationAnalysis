# Customer Segmentation Analysis using K-Means Clustering

## Project Overview

This project performs **Customer Segmentation Analysis** using the K-Means Clustering algorithm. The objective is to identify different groups of customers based on their annual income and spending behavior, enabling businesses to develop targeted marketing strategies and improve customer satisfaction.

This project was completed as part of the **Cognevance Technologies – Data Analytics & Business Intelligence Internship (Level 2 - Intermediate)**.

---

## Objectives

* Analyze customer demographic and spending data.
* Perform data cleaning and preprocessing.
* Explore customer behavior using data visualization.
* Apply the K-Means clustering algorithm.
* Identify valuable customer segments.
* Generate business insights and recommendations.

---

## Dataset

**Dataset Name:** Mall_Customers.csv

The dataset contains **200 customer records** with the following attributes:

| Feature                | Description                         |
| ---------------------- | ----------------------------------- |
| CustomerID             | Unique customer identifier          |
| Gender                 | Customer gender                     |
| Age                    | Customer age                        |
| Annual Income (k$)     | Annual income in thousand dollars   |
| Spending Score (1-100) | Spending score assigned by the mall |

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn (K-Means & StandardScaler)

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Clean and preprocess the data
5. Calculate statistical measures using NumPy
6. Visualize customer data
7. Standardize selected features
8. Determine the optimal number of clusters using the Elbow Method
9. Apply K-Means Clustering
10. Visualize customer segments
11. Generate business insights
12. Prepare the final report

---

## Project Structure

```text
cognevance_customerSegmentationAnalysis/

│── dataset/
│     Mall_Customers.csv

│── notebook/
│     Customer_Segmentation.ipynb

│── src/
│     customer_segmentation.py

│── images/
│     age_distribution.png
│     income_distribution.png
│     spending_distribution.png
│     elbow_method.png
│     customer_segments.png
│     cluster_centroids.png

│── report/
│     Business_Insights_Report.pdf

│── README.md

│── requirements.txt
```

---

## Data Preprocessing

The following preprocessing steps were performed:

* Loaded dataset using Pandas
* Checked for missing values
* Verified data types
* Removed unnecessary attributes from clustering
* Selected Annual Income and Spending Score as clustering features
* Standardized the selected features using StandardScaler

---

## Exploratory Data Analysis

The following visualizations were created:

* Age Distribution Histogram
* Annual Income Distribution Histogram
* Spending Score Distribution Histogram
* Customer Segmentation Scatter Plot
* Elbow Method Graph
* Cluster Centroid Visualization

---

## Machine Learning Model

**Algorithm:** K-Means Clustering

The Elbow Method was used to determine the optimal number of clusters. The analysis indicated that **K = 5** provides the best clustering performance for this dataset.

---

## Business Insights

* Premium customers (high income and high spending) are ideal candidates for VIP memberships and exclusive offers.
* High-income customers with low spending represent an opportunity for personalized marketing campaigns.
* Customers with low income but high spending can be targeted with affordable product bundles and seasonal promotions.
* Moderate customers can be retained through loyalty programs and personalized communication.
* Customer segmentation helps businesses improve marketing efficiency and increase customer retention.

---

## Results

* Successfully segmented customers into five distinct groups.
* Identified high-value customer segments.
* Generated visual insights through clustering and data visualization.
* Produced actionable business recommendations for targeted marketing.

---

## How to Run the Project

1. Clone this repository.

```bash
git clone https://github.com/yourusername/cognevance_customerSegmentationAnalysis.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells sequentially.

---

## Requirements

```text
pandas
numpy
matplotlib
scikit-learn
jupyter
```

---

## Future Improvements

* Include additional customer attributes such as purchase history.
* Compare K-Means with DBSCAN and Hierarchical Clustering.
* Develop an interactive dashboard using Power BI or Tableau.
* Automate customer segmentation using scheduled data updates.

---

## Author

**Raaid Farhan M**

Data Analytics & Business Intelligence Internship

Cognevance Technologies
