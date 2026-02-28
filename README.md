📊 Customer Review Clustering for Market Research
🚀 Project Overview

This project applies Unsupervised Machine Learning (K-Means Clustering) to analyze Amazon product data and group similar products based on patterns in pricing, category, and review-related features.

The objective is to identify meaningful clusters that help businesses understand product positioning, customer perception, and market segmentation.

🎯 Objective

Analyze real-world Amazon dataset

Perform data cleaning and preprocessing

Apply K-Means clustering to group similar products

Extract actionable insights for business decision-making

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📁 Repository Structure
Customer-Review-Clustering/
│
├── Clustering_customer_reviews.ipynb
├── amazon.csv
├── requirements.txt
└── README.md
▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/swarupakumari/Customer-Review-Clustering.git
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the notebook
jupyter notebook

Open:
Clustering_customer_reviews.ipynb

⚙️ Project Workflow
1️⃣ Data Cleaning & Preprocessing

Removed missing/null values

Cleaned and formatted dataset columns

Converted price values into numeric format

Selected relevant features for clustering

2️⃣ Exploratory Data Analysis (EDA)

Analyzed distribution of product categories

Visualized pricing trends

Extracted basic statistical insights

3️⃣ Feature Engineering

Selected meaningful numerical features

Applied feature scaling (standardization)

Prepared structured dataset for model training

4️⃣ K-Means Clustering

Implemented K-Means algorithm using Scikit-learn

Used the Elbow Method to determine optimal number of clusters

Assigned cluster labels to each product

5️⃣ Visualization

Visualized clusters using scatter plots

Compared cluster characteristics

Interpreted segmentation patterns

📌 Scope & Business Impact
🔹 Customer Grouping

Clustering helps group similar products or customer behavior patterns, enabling better market segmentation.

🔹 Understanding Customer Sentiment Trends

Helps identify what customers prefer or dislike based on grouped patterns.

🔹 Product Improvement

Common feature trends across clusters reveal improvement opportunities.

🔹 Better Marketing Strategies

Cluster-based segmentation allows personalized marketing campaigns.

🔹 Trend Identification

Detects pricing tiers (budget, mid-range, premium) and evolving market patterns.

🧠 About the Algorithm – K-Means

K-Means Clustering is an unsupervised learning algorithm used to group similar data points into clusters.

🔎 Working of K-Means Algorithm:

1.Select the number of clusters (K)

2.Randomly initialize K centroids

3.Assign each data point to the nearest centroid

4.Recalculate centroids as the mean of assigned points

5.Repeat assignment and update steps until centroids stabilize

6.Final clusters represent grouped data patterns
