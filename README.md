# Bank Customer Segmentation using Apache Spark’s PySpark
Unlocking Insights from Banking Data 🚀 - Dive into the fascinating world of bank customer segmentation using PySpark! Discover how we decode customer behavior to create unique segments for better marketing, all while having a blast with Apache Spark's magical powers. Join us on this data-driven adventure!

## Group Information
- Team Members:
  - AbdelHafez, Yasmine (20398568)
  - El-Ghobashy, Manar (20398569)
  - El-Zahy, Yara (20398570)
  - Sabry, Yasmine (20398566)

## Introduction
This project explores bank customer segmentation using Apache Spark's PySpark. PySpark is a Python API for Apache Spark, a distributed computing platform. We will utilize PySpark's capabilities for data analysis, machine learning, and clustering to create valuable customer clusters. These clusters can be used for targeted promotions, market expansion, and attracting new customers.

## Data Collection
We used the "Prediction of Churning Credit Card Customers" dataset, which contains customer information related to credit card usage and demographics. The dataset has 10128 rows and 23 columns, including features such as age, gender, education, and card category. Our goal is to predict customer attrition and segment customers based on their credit card characteristics.

## Unsupervised Learning Model
In this project, we apply unsupervised learning techniques to segment customers. Here's an overview of the process:

### Data Preparation
- Installation and loading of PySpark and required libraries.
- Loading the dataset into PySpark.
- Data schema inspection.
- Data cleaning, including handling duplicates, NaN, and null values.
- Encoding categorical variables.
- Feature extraction and vector assembly.

### The Model
We employ the K-means clustering algorithm to partition the dataset into clusters based on card categories. The main features used for clustering include customer age, gender index, average open-to-buy ratio, credit limit, total transaction amount, and total transaction count.

## Model Evaluation
We evaluate our K-means model using two methods:

### Principal Component Analysis (PCA)
PCA is used for dimensionality reduction, visualization, and identifying significant features. We project data onto the top three principal components to understand data variance.

### Silhouette Coefficient
The silhouette score measures the similarity of data points within clusters compared to other clusters. A higher silhouette score indicates better clustering. Our model achieved a score of approximately 0.7554, indicating good performance.

## Conclusion
This project demonstrates the use of Apache Spark’s PySpark for customer segmentation. By selecting relevant features and applying the K-means clustering algorithm, we successfully segmented bank customers based on card categories. This unsupervised learning approach achieved a strong clustering performance.

## References
[1] zhyli, “Prediction of Churning Credit Card Customers,” Dec. 2020, doi: 10.5281/ZENODO.4322342.

## Workload

| Task               | Team Member(s)            |
|--------------------|----------------------------|
| Data Collection    | AbdelHafez, ElGhobashy, ElZahy, Sabry |
| Data Preparation   | Sabry                      |
| Feature Engineering| ElZahy                     |
| Model Building     | ElGhobashy                 |
| Model Evaluation   | AbdelHafez, ElGhobashy, ElZahy, Sabry |
