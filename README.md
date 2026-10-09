# Microservice_Performance_Profiling_-_Anomaly
Analyzed microservice performance metrics using Python and K-Means clustering to identify performance patterns and potential anomalies. Applied data preprocessing, feature scaling, and clustering evaluation to group services based on CPU usage, latency, response time, error rate, and availability.

<img width="541" height="314" alt="Screenshot 2026-10-09 153707" src="https://github.com/user-attachments/assets/484c7eb2-3beb-4490-8734-0e0349fb6941" />


1. Data Loading: Imported microservice performance data using Pandas for analysis.

2. Data Cleaning: Checked for missing values and removed duplicate records to improve data quality.

3. Exploratory Data Analysis (EDA): Used descriptive statistics to understand the dataset and its performance metrics.

4. Data Visualization: Created histograms, box plots, correlation heatmaps, and pair plots to explore data distributions and relationships.

5. Feature Scaling: Applied StandardScaler to standardize numerical features before clustering.

6. K-Means Clustering: Used the K-Means algorithm to group microservice performance records into four clusters.

7. Optimal Cluster Selection: Applied the Elbow Method to evaluate the suitable number of clusters.

8. Model Evaluation: Used the Silhouette Score to compare clustering quality across different cluster counts.

9. Cluster Profiling: Calculated average metrics for each cluster to understand differences in microservice performance.

10. Performance Analysis: Visualized clusters using CPU usage, latency, response time, error rate, and availability to identify performance patterns and investigate potentially problematic groups.
