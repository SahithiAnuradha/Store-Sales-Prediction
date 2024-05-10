
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

The dataset contains historical sales data for 45 Walmart stores and the stores located in different regions throughout the country for the years 2010 - 2012.

The dataset size is **~100000**

train.csv features:

- Store - the store number
- Dept - the department number
- Date - the week
- Weekly_Sales - sales for the given department in the given store
- IsHoliday - whether the week is a special holiday week

features.cs features:

- Store - the store number
- Date - the week
- Temperature - the average temperature in the region
- Fuel_Price - the cost of fuel in the region
- MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011 and is not available for all stores all the time. Any missing value is marked with a NA.
- CPI - the consumer price index
- Unemployment - the unemployment rate
- IsHoliday - whether the week is a special holiday week

## Usage

1. Download or clone the repository containing the project code and datasets.
2. Install the necessary Python libraries as mentioned above.
3. Open the Jupyter Notebook (`walmart_project_final_code (2).ipynb`) and run the cells sequentially to preprocess the data, perform exploratory data analysis, and apply machine learning models for association rule mining and product recommendation.

## Key Components

- **Data Preprocessing**: Cleaning and merging dataset files for analysis.
- **Exploratory Data Analysis (EDA)**: Analyzing sales on normal days, on holidays, product popularity, and reorder rates.
- **Machine Learning Models**: Applying algorithms like Linear Regressio, Ridge Regression, Decision Tree, Random Forest etc., on the data set.

## Results obatained for different Machine Learning models
**Linear Regression:**
- Training dataset WMAE is 14808.15
- Validation dataset WMAE is 14834.85

**Ridge Regression:**
- Training dataset WMAE is 14808.15
- Validation dataset WMAE is 14834.85

**Decision Tree:**
- Training dataset WMAE is 14808.15
- Validation dataset WMAE is 1709.88

**Random Forest:**
- Training dataset WMAE is 542.21
- Validation dataset WMAE is 1348.38

**Extra Trees:**
- Training dataset WMAE is 609.17
- Validation dataset WMAE is 1562.77

For detailed experimental results and hyper parameter tuning results refer to the report.

## Acknowledgments

This project was a collaborative effort by Anuradha Sahithi Padavala, Valipe Soundarya Lahari, Venkata Ramana Rohith Neralla, Naga Govardhan Munagala, leveraging public datasets for educational and research purposes.
