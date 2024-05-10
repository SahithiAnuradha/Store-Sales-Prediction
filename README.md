
# Store Sales Prediction:WALMART

## Overview

The sales forecast is a projected measure of how a market will respond to a company’s go-to-market efforts. Walmart is one of the largest retail and wholesale businesses in the world, and they should have accurate forecasts for their sales in various departments. In this project, we experimented with different machine-learning models with the dataset provided by Kaggle for the “Walmart Recruiting - Store Sales Forecasting” competition. Our findings indicate
that Random Forest and the Extra Trees models are the most promising techniques for this problem.

## Authors
- Anuradha Sahithi Padavala 
- Valipe Soundarya Lahari
- Venkata Ramana Rohith Neralla
- Naga Govardhan Munagala 
- College of Engineering and Computer Science University of Central Florida, Orlando, Florida – 32816 

## Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Libraries

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost catboost lightgbm
```

## Dataset

The dataset is anonymized and contains sample orders from Instacart users over time, including product orders, departments, and aisles information. It features:

- Orders
- Products
- Aisles
- Departments

## Usage

1. Download or clone the repository containing the project code and datasets.
2. Install the necessary Python libraries as mentioned above.
3. Open the Jupyter Notebook (`walmart_project_final_code (2).ipynb`) and run the cells sequentially to preprocess the data, perform exploratory data analysis, and apply machine learning models for association rule mining and product recommendation.

## Key Components

- **Data Preprocessing**: Cleaning and merging dataset files for analysis.
- **Exploratory Data Analysis (EDA)**: Analyzing order patterns, product popularity, and reorder rates.
- **Machine Learning Models**: Applying algorithms like Logistic Regression, Random Forest, AdaBoost, and others for predicting product reorders.
- **Association Rule Mining**: Using Apriori and FP-Growth algorithms to find product associations.
- **Collaborative Filtering**: Implementing user-based and item-based collaborative filtering for product recommendations.

## Acknowledgments

This project was a collaborative effort by Anuradha Sahithi Padavala, Valipe Soundarya Lahari, Venkata Ramana Rohith Neralla, Naga Govardhan Munagala, leveraging public datasets for educational and research purposes.
