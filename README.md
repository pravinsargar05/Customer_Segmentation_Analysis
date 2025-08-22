# Customer Segmentation Analysis Using K-Means Clustering
## Objective
The objective of this project is to perform customer segmentation for a retail business. By clustering customers based on their spending habits and demographics, we can identify distinct customer groups. This allows the business to develop personalized marketing strategies, improve customer retention, and optimize resource allocation.

## Tools & Technologies
- Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter

## Project Steps
- Data Loading & Cleaning: Loaded the dataset using Pandas and performed initial checks for missing values and data types.
- Exploratory Data Analysis (EDA): Used Matplotlib and Seaborn to visualize data distributions and identify potential relationships between features.
- Feature Preprocessing: Selected and scaled the Annual Income and Spending Score features for clustering.
- Model Building: Applied the K-Means algorithm. Used the Elbow Method and Silhouette Score to determine the optimal number of clusters (k=5).
- Cluster Visualization & Interpretation: Visualized the final clusters and analyzed their characteristics to provide actionable business insights.

## Results & Insights
- Segment 1: Cautious Spenders  - Low income, low spending score.
- Segment 2: High-Income, Low-Spenders  - High income, low spending score.
- Segment 3: Average Joes  - Mid-range income and spending.
- Segment 4: High-Spenders  - Low income, high spending score.
- Segment 5: Rich & Reckless  - High income, high spending score.
