#  Applied Data Science (STAT GR 5243) Project 1: Flight Delay Analysis

## Overview

This repository contains the full codebase and report for our Flight Delay Analysis project. The objective of this project is to analyze commercial flight delay patterns and transform raw operational flight data from 2024 into a clean, analysis-ready dataset suitable for EDA and predictive modeling.

The project includes the complete data pipeline:

- Data acquisition
- Data cleaning and preprocessing
- Feature engineering
- Exploratory data analysis
- Final report and findings

The original dataset was obtained from Kaggle:

https://www.kaggle.com/datasets/hrishitpatil/flight-data-2024

This dataset is derived from the U.S. Bureau of Transportation Statistics (BTS) On-Time Performance database and contains detailed operational records for domestic commercial flights.

---

## Important Notes About the Datasets

The original raw dataset and cleaned dataset are very large and exceed GitHub’s file size limits. Therefore, only the first **10,000 rows** of each dataset are included in this repository, under the folder `Data/`:

- `flight_data_2024_sample.csv`: this is the sample of the **original** raw dataset downloaded from Kaggle. 
- `flights_clean_feature_engineered_sample.csv`: this is a sample of the **final** cleaned and preprocessed dataset. 

These sample files are provided to:

- Demonstrate the full data pipeline
- Allow the code to run successfully
- Ensure reproducibility of the analysis

The code in this repository works identically on the full dataset that was downloaded from Kaggle.

---

## Repository Structure
```
├── Data/
│   ├── flight_data_2024_sample.csv
│   └── flights_clean_feature_engineered_sample.csv
│
├── Notebooks/
│   ├── datacleaning.ipynb
│   ├── flight_feature_engineering.ipynb
│   └── EDA.ipynb
│
├── Report/
│   └── flight_delay_report.pdf
│
└── README.md
```
--- 

## Running the Code with Full Dataset

1. Install all necessary libraries and dependencies: 

```bash
pip install pandas numpy matplotlib seaborn jupyter
```
Start Jupyter Notebook: 

```bash
jupyter notebook
```

2. Download the dataset from Kaggle:

https://www.kaggle.com/datasets/hrishitpatil/flight-data-2024

In our `Data/` folder, there is a sample of the data under `flight_data_2024_sample.csv`. 

Run the Jupyter notebooks stored under the `Notebooks` folder in the exact order below, and update file paths in the notebooks as necessary:

1. datacleaning.ipynb
2. flight_feature_engineering.ipynb
3. EDA.ipynb

The second notebook will produce the final cleaned and preprocessed version of the data, a sample of which is available in our `Data/` folder under `flights_clean_feature_engineered_sample.csv`. 

Aside from changes in file paths, the pipeline will run without modification.

--- 

## Reproducibility

All data cleaning, feature engineering, and EDA steps are fully reproducible using the code provided in this repository.

## Authors 

Helena Li, Crystal Guo, Nikhil Shanbhag, Yijing Zhang
