
# Market Basket Analysis: Instacart

## Overview

Market Basket Analysis for Instacart aims to enhance the online grocery shopping experience by applying machine learning models to recommend products based on customer's shopping habits. The project leverages the Instacart dataset to identify patterns and recommend products that are likely to be bought together or in subsequent orders.

## Authors
- Valipe Soundarya Lahari
- Venkata Ramana Rohith Neralla
- Anuradha Sahithi Padavala 
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

This project was a collaborative effort by Sai Kiran Bellamkonda, Balaganesan Kumaran, and Vaishnavi Mandula, leveraging public datasets for educational and research purposes.

---

# Walmart Sales Forecasting Project

## Overview

The Walmart project focuses on predicting weekly sales using historical data. The project utilizes machine learning models to forecast sales based on factors like store features, promotional information, and economic indicators.

## Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Libraries

Required Python packages:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost catboost lightgbm
```

## Dataset

The dataset includes weekly sales data from Walmart stores, featuring:

- Sales
- Store information
- Promotional data
- Economic features

## Usage

1. Download or clone the repository containing the project code and datasets.
2. Ensure all necessary Python libraries are installed.
3. Load the Jupyter Notebook (`walmart_project_final_code (2).ipynb`) and execute the cells in order to train models and make predictions on weekly sales.

## Key Components

- **Data Loading**: Importing datasets for training and testing.
- **Data Preprocessing**: Merging store information with features and sales data.
- **Feature Engineering**: Extracting and selecting relevant features for the models.
- **Model Training**: Applying models such as XGBoost, LightGBM, and CatBoost for sales prediction.

## Acknowledgments

The Walmart sales forecasting project utilizes publicly available data for the purpose of educational and research exploration.
