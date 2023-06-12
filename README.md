# Customer Segmentation Project

Customer Segmentation is one of the most important applications of unsupervised learning. By using clustering techniques, B2C (Business to Customers) companies can identify different segments of customers based on their similarities in various marketing-relevant aspects such as gender, age, interests, and spending habits. This allows companies to target specific customer segments and tailor their marketing strategies accordingly.

## Project Overview

In this Data Science Project, we will implement customer segmentation in Python. The goal is to identify distinct customer segments based on their characteristics. We will explore the dataset, perform a univariate analysis on each feature, and then apply the K-means clustering algorithm to segment the customers.

## Dataset

The dataset consists of a CSV file containing the following features for each customer:

- CustomerIDs
- Age
- Gender
- Annual Income
- Spending Score

## Getting Started

To run the project, follow these steps:

1. Clone the repository.
2. Make sure you have the required dependencies installed, including pandas, numpy, matplotlib, and seaborn.
3. Import the necessary libraries in your Python environment.
4. Load the dataset using the provided CSV file.
5. Explore the data and perform a univariate analysis on each feature.
6. Determine the optimal number of clusters using the Silhouette method.
7. Apply K-means clustering to segment the customers.
8. Visualize the clustering results using PCA with 2 components.

## Results

### Gender

We analyzed the gender distribution in the dataset using a bar plot and a pie chart. The results showed that the percentage of females is 56%, while the percentage of males is 44% .

### Age

The age feature was analyzed using a histogram and a box plot. The majority of customers fall within the age range of 30-35. The minimum age is 18, and the maximum age is 70 .

### Annual Income

The annual income feature was explored using a histogram and a density plot. The distribution of annual income appears to be normal, with a peak around an average income of 70. The minimum income is 15, and the maximum income is 137 .

### Spending Score

The spending score feature was analyzed using a box plot and a distribution plot. The majority of customers have a spending score between 40 and 50 .

### K-means Clustering

We applied the K-means clustering algorithm to segment the customers based on their features. The optimal number of clusters was determined to be 6 using the average silhouette width method . The clustering results were visualized using PCA with 2 components. The clusters were labeled as follows:

- Cluster 0 and 5: Customers with medium PCA2 and high PCA1.
- Cluster 1: Customers with high PCA2 and low PCA1.
- Cluster 2: Customers with medium PCA1 and medium PCA2.
- Cluster 3: Customers with high PCA2 and medium annual income.
- Cluster 4: Customers with medium PCA1 and low PCA2 .

## Conclusion

Customer segmentation through clustering allows businesses to gain insights into their customer base and make informed decisions regarding product development, marketing strategies, and customer targeting. By understanding customer characteristics and preferences, companies can personalize their offerings and improve customer satisfaction.

---

Please note that the code and analysis provided in this README file are based on the code snippet you provided. Make sure to adapt and modify the code as needed to fit your specific requirements and dataset.

If you have any further questions or need assistance, feel free to reach out.

