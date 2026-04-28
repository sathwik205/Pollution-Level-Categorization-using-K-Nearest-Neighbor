# Pollution-Level-Categorization-using-K-Nearest-Neighbor
🌍 Pollution Level Categorization using K-Nearest Neighbors (KNN)

This project focuses on classifying air pollution levels into categories such as Low, Moderate, High, and Severe using the K-Nearest Neighbors (KNN) machine learning algorithm. The model analyzes various air quality indicators including particulate matter (PM2.5, PM10) and gaseous pollutants (NO₂, SO₂, CO, O₃) to determine the overall pollution level.

📌 Overview

Air pollution is a critical environmental issue that directly impacts human health and ecosystems. Accurate classification of pollution levels helps in monitoring air quality and supporting decision-making for environmental policies. This project applies a supervised learning approach where historical pollution data is used to train a model capable of predicting pollution categories for new data.

⚙️ Methodology

The workflow begins with data preprocessing, including handling missing values and normalizing feature scales to ensure fair distance calculations. Since KNN is a distance-based algorithm, feature scaling plays a crucial role in improving model performance.

The dataset is then split into training and testing sets. The KNN algorithm classifies a new data point by identifying the k closest data points in the feature space and assigning the most common category among them. Different values of k can be tested to optimize accuracy.

📊 Visualization

To better understand the structure of the dataset, dimensionality reduction techniques like t-SNE (t-distributed Stochastic Neighbor Embedding) are used to project high-dimensional pollution data into a 2D space. This helps visualize how different pollution categories cluster together and reveals overlaps or separations between classes.

📈 Evaluation

The model’s performance is evaluated using metrics such as:

Accuracy Score
Confusion Matrix
Precision, Recall, and F1-Score

These metrics provide insights into how well the model distinguishes between different pollution levels.

🚀 Applications
Real-time air quality monitoring systems
Smart city environmental dashboards
Health risk assessment tools
Government pollution control analysis
🔍 Conclusion

The KNN-based approach provides a simple yet effective method for pollution level classification. While it performs well for structured datasets, its accuracy depends on proper feature scaling and the choice of k. Visualization techniques like t-SNE further enhance understanding of the data distribution and model behavior.
