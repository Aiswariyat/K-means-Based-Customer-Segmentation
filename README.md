# K-means Based Customer Segmentation in E-commerce

This project utilizes K-means clustering and machine learning techniques to perform customer segmentation on an online retail dataset. The goal is to identify distinct customer groups to enable targeted marketing strategies and enhance customer engagement.

## Project Overview

Customer segmentation is a crucial aspect of modern retail strategies. By understanding the unique characteristics and behaviors of different customer groups, businesses can tailor their marketing efforts and improve overall customer satisfaction. This project focuses on applying K-means clustering to segment customers based on their purchasing behaviors in an e-commerce setting.

## Dataset

The dataset used in this project contains transaction data from an online retail store, including information such as:

- Invoice number
- Stock code
- Description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

## Key Steps

1. **Data Preprocessing:**
    - Loaded the dataset and handled missing values.
    - Converted data types and extracted relevant features.
    - Standardized numerical features to ensure they are on a similar scale.

2. **Exploratory Data Analysis (EDA):**
    - Performed data visualization to understand purchasing patterns.
    - Identified key metrics such as total revenue per customer, number of purchases, and average order value.

3. **Feature Engineering:**
    - Created new features such as Recency, Frequency, and Monetary (RFM) values.
    - Applied Principal Component Analysis (PCA) for dimensionality reduction.

4. **K-means Clustering:**
    - Implemented the K-means clustering algorithm to segment customers.
    - Used the Elbow method and silhouette score to determine the optimal number of clusters.
    - Analyzed the characteristics of each cluster.

5. **Model Evaluation:**
    - Evaluated the clustering results using silhouette scores and visual inspection.
    - Interpreted the clusters and provided insights for targeted marketing strategies.

## Results

- Identified 4 distinct customer segments with unique purchasing behaviors.
- Enhanced the interpretability of customer groups through PCA.
- Provided actionable insights for personalized marketing strategies.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/kmeans-customer-segmentation.git
    ```

2. Navigate to the project directory:
    ```bash
    cd kmeans-customer-segmentation
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter notebook:
    ```bash
    jupyter notebook Cust_segmentation_online_retail.ipynb
    ```

## Conclusion

This project demonstrates the application of K-means clustering for customer segmentation in an online retail context. By leveraging machine learning techniques, businesses can gain valuable insights into customer behavior and implement effective marketing strategies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project is available from the UCI Machine Learning Repository.
- Special thanks to the contributors of the open-source libraries used in this project.
