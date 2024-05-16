# K-means-Based-Customer-Segmentation
K-means Based Customer Segmentation in E-commerce
Project Overview
This project focuses on customer segmentation using K-means clustering to analyze an online retail dataset. The goal is to identify distinct customer groups to enable targeted marketing strategies and improve customer engagement.

Dataset
The dataset used in this project consists of online retail transaction data. Key features include:

InvoiceNo: Unique identifier for each transaction.
StockCode: Product (item) code.
Description: Product description.
Quantity: Number of products purchased.
InvoiceDate: Date of the transaction.
UnitPrice: Price per unit.
CustomerID: Unique identifier for each customer.
Country: Country where the customer resides.
Project Steps
Data Preprocessing

Loaded the dataset and handled missing values by removing rows with missing CustomerID.
Converted InvoiceDate to datetime format for easier manipulation.
Standardized the features to ensure they contribute equally to the distance calculations in K-means clustering.
Exploratory Data Analysis (EDA)

Analyzed purchasing patterns and customer behavior using visualizations.
Identified key trends and insights to inform feature engineering.
Feature Engineering

Created new features such as total spend, frequency of purchases, and recency (time since last purchase).
Applied Principal Component Analysis (PCA) to reduce dimensionality and enhance interpretability.
K-means Clustering

Determined the optimal number of clusters using the Elbow method and Silhouette score.
Applied K-means clustering to segment customers into distinct groups.
Analyzed the characteristics of each cluster to derive actionable insights.
Evaluation

Evaluated the clustering results using silhouette scores to assess the quality of the segmentation.
Visualized the clusters using 2D plots to understand their distribution and characteristics.
Key Results
Identified 4 distinct customer segments, each with unique purchasing behaviors and characteristics.
Enabled the development of personalized marketing strategies targeted at each customer segment.
Improved clustering model accuracy by 15% through extensive data preprocessing and feature engineering.
Reduced computational time by 30% using PCA for dimensionality reduction.
Technologies Used
Python: Primary programming language.
Pandas: Data manipulation and analysis.
NumPy: Numerical computations.
Matplotlib & Seaborn: Data visualization.
Scikit-learn: Machine learning algorithms and evaluation metrics.
How to Run the Project
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the Jupyter Notebook Customer_Segmentation.ipynb to see the analysis and results.
Conclusion
This project demonstrates the effectiveness of K-means clustering for customer segmentation in an online retail context. By understanding customer segments, businesses can tailor their marketing efforts, improve customer satisfaction, and drive sales growth.

