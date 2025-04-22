# Customer-segmentation
Segmenting customers through the application of clustering algorithms and association rule mining using Python

# Open the notebook in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julienguyenaus/Customer-segmentation/blob/main/Github%20Customer%20Segmentation%20using%20ML%20models.ipynb)

> 📌 Note: The notebook is large (151MB) and stored with Git LFS. It may take a moment to load in Colab.

## 1. Problem Formulation
Traditional customer segmentation methods based on demographics and simple rules often lead to broad, ineffective marketing. In today’s data-rich and competitive market, businesses need AI-driven solutions that can uncover complex customer behaviors for more personalized engagement.

This project addresses that need by applying clustering algorithms and association rule mining to segment customers and identify purchasing patterns:

- Clustering (e.g., K-Means, Gaussian Mixture Models): Groups customers based on behavior and purchase history.

- Association Rule Mining: Reveals frequently bought item combinations to support cross-selling and upselling.

- Feature Engineering & Evaluation: Enhances model accuracy with meaningful features like purchase frequency, product variety, and department preferences.

- These approaches help businesses better understand customer needs, improve targeting, and optimize marketing strategies.

## 2. Data Collection
This project uses publicly available datasets to ensure scalability and reproducibility. The selected dataset must include:

- A large volume of transactions (thousands+)

- Structured format compatible with data analysis tools

- Rich features such as timestamps, product categories, and customer IDs

The Kaggle eCommerce Dataset for Predictive Marketing was chosen due to its completeness, accessibility, and relevance to the project's goals.
📦 Dataset Link: [Kaggle - eCommerce Dataset 2023](https://www.kaggle.com/datasets/hunter0007/ecommerce-dataset-for-predictive-marketing-2023)

## 3.Methodlogy
This project followed a structured approach to segment customers and uncover purchasing patterns using clustering algorithms and association rule mining:

  a. Data Preprocessing & Exploration

  - Cleaned and structured over 2 million transactions from a public eCommerce dataset.

  - Engineered features based on RFM (Recency, Frequency, Monetary), time-based behavior, department preferences, loyalty indicators, and shopping patterns.

  - Scaled features using MinMaxScaler and reduced dimensionality via PCA to improve model performance.

  b. Clustering Analysis

  - Applied and compared K-Means, DBSCAN, Gaussian Mixture Models, and Hierarchical Clustering.

  - Evaluated model performance using Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index.

  - K-Means with 3 clusters (on 2 PCA components) was identified as the most effective for clean separation and business insights.

  c. Association Rule Mining

  - Discovered frequently co-purchased items to support personalized recommendations and upselling strategies.

## 4. Conclusion
By leveraging clustering algorithms and association rule mining, we successfully uncovered distinct customer segments and purchasing patterns from a real-world eCommerce dataset.
The results provide valuable insights into customer behavior, enabling businesses to craft targeted marketing strategies, optimize inventory management, and enhance customer loyalty. The integration of feature engineering, dimensionality reduction, and rigorous model evaluation ensures both accuracy and interpretability.
