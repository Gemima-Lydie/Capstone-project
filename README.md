# Capstone-project
### README for Fashion Trend Prediction Using CLIP and t-SNE
## link to notbook: https://colab.research.google.com/drive/19PrFO4xo8xqwX6VCLhv-MFg-keq_wMZU?usp=sharing

---

#### Project Overview

This project leverages advanced machine learning techniques to predict emerging fashion trends by analyzing runway images using CLIP embeddings and dimensionality reduction methods like t-SNE and PCA. The project focuses on uncovering underlying patterns in fashion data, enabling the identification of fine-grained visual styles and their potential application across various domains beyond apparel, such as accessories, home furnishings, and automobiles.

#### Key Components

1. **Data Preprocessing**:
   - **CLIP Embeddings**: Utilizes CLIP (Contrastive Language–Image Pre-training) to encode fashion images into feature vectors that capture semantic attributes.
   - **Feature Extraction**: Image features are extracted and saved for further analysis and clustering.

2. **Dimensionality Reduction**:
   - **PCA (Principal Component Analysis)**: Reduces the dimensionality of the data to visualize broad patterns in fashion items.
   - **t-SNE (t-Distributed Stochastic Neighbor Embedding)**: Used for detailed clustering and visualization of the fashion items to reveal nuanced relationships and similarities.

3. **Clustering**:
   - **K-Means Clustering**: Applied to both PCA and t-SNE results to group similar fashion items and understand their distribution.
   - **Distance Analysis**: Compares the Euclidean distances between selected fashion items before and after t-SNE, providing insights into the changes in similarity.

4. **Trend Forecasting**:
   - **Exponential Smoothing**: Implements time series forecasting to predict future trends based on historical fashion data, excluding irrelevant categories like "Personal Care" and "Accessories."

#### Project Structure

- **Data**: Includes the dataset of fashion images with associated labels.
- **Scripts**: Python scripts for preprocessing, feature extraction, dimensionality reduction, clustering, and forecasting.
- **Results**: Visualization of PCA, t-SNE, and the comparison of Euclidean distances, along with trend forecasting plots.

#### Usage

1. **Setup**:
   - Install the required Python packages listed in the `requirements.txt`.
   - Load the dataset and preprocess it using the provided scripts.

2. **Run the Analysis**:
   - Execute the scripts for feature extraction, dimensionality reduction, and clustering.
   - Analyze the results using the provided visualization tools.

3. **Forecast Trends**:
   - Apply Exponential Smoothing to the preprocessed data to predict future trends.

#### Conclusion

The insights generated from this project can significantly aid in predicting fashion trends, offering valuable information to designers and retailers, and extending applications to other industries where visual style is crucial.

---

This README provides a concise overview of the project's goals, methodologies, and how to use the provided resources for predicting fashion trends.
