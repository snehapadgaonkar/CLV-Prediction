# Predicting Customer Lifetime Value through Behavioral Segmentation

## Project Overview

This project focuses on predicting Customer Lifetime Value (CLV) using a classification model based on customer purchasing behavior, frequency, and engagement metrics. The model categorizes customers into segments like 'High-Valued' and 'Low-Valued' to enhance targeted marketing strategies.

## Dataset

### Source
[Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

### Description
The dataset includes transactions from December 1, 2010, to December 9, 2011, for a UK-based online retailer specializing in unique gifts.

## Key Concepts

- **Customer Lifetime Value (CLTV)**: A measure of the total revenue expected from a customer over their relationship with a business.
- **RFM Analysis**: Recency, Frequency, and Monetary metrics to analyze customer behavior.

## Data Pre-Processing

1. **Load Dataset**: Import the dataset using Pandas.
2. **Data Cleaning**: Handle missing values and filter out invalid data (e.g., negative quantities).
3. **Feature Engineering**: Generate RFM features and define target variable for classification.

## Model Training and Evaluation

### Algorithms Used
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest
- Naive Bayes

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC Curve

## Conclusion

The project provides a framework for predicting Customer Lifetime Value through behavioral segmentation, enabling businesses to identify high-value customers to optimize their marketing strategies.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/snehapadgaonkar/CLV-Prediction.git
   cd repo-name
2. **Load the Dataset**: 
   Ensure you have the dataset in the specified location or update the path in the notebook.
3. **Run the Notebook**: 
   Open the Jupyter Notebook and follow the steps for data preprocessing, feature engineering, and model evaluation.
