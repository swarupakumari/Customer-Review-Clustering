📊 Customer Review Clustering for Market Research
🚀 Project Overview

This project applies Unsupervised Machine Learning (K-Means Clustering) to analyze Amazon customer reviews and group similar feedback patterns.

The goal is to identify meaningful clusters in customer reviews to help businesses understand product perception and customer behavior.

🎯 Objective

Analyze real-world Amazon review dataset

Perform text preprocessing and feature engineering

Apply K-Means clustering to group similar reviews

Extract actionable insights for market research

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

Clone the repository:

git clone https://github.com/swarupakumari/Customer-Review-Clustering.git

Install dependencies:

pip install -r requirements.txt

Open Jupyter Notebook:

jupyter notebook

Run Clustering_customer_reviews.ipynb


⚙️ Project Workflow
1️⃣ Data Cleaning & Preprocessing

Removed missing/null values

Cleaned and formatted text columns

Converted price values to numeric format

Feature selection for clustering

2️⃣ Exploratory Data Analysis (EDA)

Distribution analysis of product categories

Pricing trends visualization

Basic statistical insights

3️⃣ Feature Engineering

Selected relevant numerical features

Scaled data using standardization

Prepared dataset for clustering

4️⃣ K-Means Clustering

Implemented K-Means algorithm using Scikit-learn

Used Elbow Method to determine optimal number of clusters

Assigned cluster labels to products

5️⃣ Visualization

Visualized clusters using scatter plots

Compared cluster characteristics



# Clustering-of-customer-reviews-for-market-research
1) OBJECTIVE
To analyze and cluster customer reviews to identify common themes, sentiments, and patterns in customer feedback, thereby enabling businesses to make informed decisions to improve products, services, and customer experience.

2) Here’s the scope of clustering customer reviews in simple terms: 

Grouping Customers: Clustering helps in grouping customers with similar opinions or behaviors. This makes it easier to 
                    understand different types of customers. 

Understanding Feelings: By clustering reviews, businesses can see what customers like or dislike. This helps in knowing how 
                    happy customers are and what needs to be improved. 

Better Marketing: With clustered data, companies can create more personalized ads and offers that appeal to specific groups 
                    of customers. 

Improving Products: Clustering can show common problems or desired features in products, guiding businesses to make better 
                    products. 

Enhancing Service: Knowing different customer groups helps in providing better service, making customers happier and more 
                    loyal. 

Spotting Trends: Clustering can reveal new trends and changes in customer preferences, helping businesses stay ahead.

3)Algorithm(KMeans)

K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning.
The main aim of this algorithm is to minimize the sum of distances between the data point and their corresponding clusters.
How does the K-Means Algorithm Work? The working of the K-Means algorithm is explained in the below steps:

Step-1: Select the number K to decide the number of clusters.
Step-2: Select random K points or centroids. (It can be other from the input dataset).
Step-3: Assign each data point to their closest centroid, which will form the predefined K clusters.
Step-4: Calculate the average and place a new centroid of each cluster.
Step-5: Repeat the third steps, until we don't get a saturation point ........ 
Step-6: Now the centroid point will be terms as mean centroid value.
Step-7: The model is ready.
