# Airbnb NYC Data Cleaning Challenge

## Project Overview

This project involves cleaning and preprocessing the [Airbnb NYC dataset]([link-to-dataset](https://www.kaggle.com/datasets/thedevastator/airbnbs-nyc-overview?resource=download)) from Kaggle. The dataset includes details about Airbnb listings in New York City. The primary goal was to handle missing values, outliers, and inconsistencies to prepare the dataset for further analysis or modeling.

## Dataset

- **Original Dataset:** [`Airbnb_NYC.csv`](https://github.com/fayzankj/airbnb-nyc-data-cleaning/blob/main/Airbnb_NYC.csv)
- **Cleaned Dataset:** [`cleaned_airbnb_nyc.csv`](https://github.com/fayzankj/airbnb-nyc-data-cleaning/blob/main/cleaned_airbnb_nyc.csv)

## Jupyter Notebook

The data cleaning process is thoroughly documented in the Jupyter Notebook:

- [`Data_Cleaning_Notebook.ipynb`](https://github.com/fayzankj/airbnb-nyc-data-cleaning/blob/main/Data_Cleaning_Notebook.ipynb)

## Project Steps

1. **Initial Data Exploration**
   - Loading the dataset
   - Overview of the data
   - Checking for missing values and duplicates

2. **Data Cleaning**
   - Handling missing values
   - Removing duplicates
   - Dealing with inconsistent data
   - Handling outliers

3. **Data Preprocessing**
   - Feature engineering
   - Data type conversion

## Key Findings

- **Missing Values:** Identified and addressed missing values in columns such as `name`, `host_name`, `reviews_per_month` and `last_review`.
- **Duplicates:** Removed duplicate entries to ensure dataset integrity.
- **Inconsistent Data:** Standardized values in columns with inconsistent entries.
- **Outliers:** Detected and removed outliers from numerical columns like `price`.

## Getting Started

To run the Jupyter Notebook locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/fayzankj/Airbnb-NYC-Data-Cleaning.git
