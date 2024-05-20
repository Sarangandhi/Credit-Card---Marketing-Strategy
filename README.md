# Credit Card - Marketing Stretergy Using Clustering Algorithm

## Introduction

This project aims to perform clustering analysis on a credit card dataset to segment customers based on their credit card usage patterns. By leveraging machine learning techniques, particularly K-means clustering, the project seeks to identify distinct groups of customers with similar behaviors and characteristics. Understanding these segments can help financial institutions tailor their services and marketing strategies to better meet the needs of different customer segments.

## Dataset

The dataset used in this project, Credit Card_Clustering.csv, contains information about credit card holders, including features such as balance, credit limit, minimum payments, and more. Before performing clustering, the dataset is preprocessed to handle missing values and normalize the data to ensure meaningful clustering results.

## Installation

To run this project, ensure you have the following dependencies installed:

```python
NumPy
pandas
scikit-learn
matplotlib
seaborn
Yellowbrick
```
You can install the dependencies using pip:
```pip install numpy pandas scikit-learn matplotlib seaborn yellowbrick```

## Usage

1. Clone the repository: git clone https://github.com/Sarangandhi/Credit-Card---Marketing-Strategy.git

2. cd ```Credit-Card-Clustering```

3. Ensure your dataset Credit Card_Clustering.csv is in the project directory.

4. Run the Jupyter notebook or Python script to perform clustering analysis.

    ```jupyter notebook Credit_Card_Clustering.ipynb```
5. Follow the instructions in the notebook or script to execute the code step by step.

# Methodology

**Data Preprocessing:**
Handle missing values using KNN imputation.
Normalize the data to ensure all features contribute equally to clustering.

**Optimal K Selection:**
Use the elbow method with the Yellowbrick library to determine the optimal number of clusters.

**Clustering:**
Perform K-means clustering with the optimal number of clusters.

**Evaluate:**
Evaluate clustering performance using silhouette score.

**Visualization:**
Reduce dimensionality using PCA for visualization.
Plot clusters in two dimensions to visualize segmentations.

**Results:**
The clustering analysis reveals distinct segments of credit card holders based on their usage patterns. Each segment represents a group of customers with similar characteristics, allowing financial institutions to tailor their services to better meet the needs of different customer segments.

**License:**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contact**
For any inquiries or feedback, please contact:

**Email:** sarangandhi66@gmail.com

**LinkedIn:** https://www.linkedin.com/in/saranraj-gandhi/

For any further questions, feel free to reach out.
