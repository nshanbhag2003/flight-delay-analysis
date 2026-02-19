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

## Important Note About Dataset Size

The original raw dataset and cleaned dataset are very large and exceed GitHub’s file size limits. Therefore, only the first **5000 rows** of each dataset are included in this repository:

- `raw_sample.csv`
- `cleaned_sample.csv`

These sample files are provided to:

- Demonstrate the full data pipeline
- Allow the code to run successfully
- Ensure reproducibility of the analysis

The code in this repository works identically on the full dataset that was downloaded from Kaggle.

---

## Repository Structure
```
├── data/
│   ├── raw_sample.csv
│   └── cleaned_sample.csv
│
├── notebooks/
│   ├── datacleaning.ipynb
│   ├── flight_feature_engineering.ipynb
│   └── EDA.ipynb
│
├── report/
│   └── flight_delay_report.pdf
│
├── requirements.txt
│
└── README.md
```
--- 

## Install required packages

```bash
pip install pandas numpy matplotlib seaborn jupyter
```
--- 

## Run the notebooks

Start Jupyter Notebook: 

```bash
jupyter notebook
```

Run the notebooks in this order:

1. datacleaning.ipynb
2. flight_feature_engineering.ipynb
3. EDA.ipynb

--- 

## Running the Code with Full Dataset

1. Download the dataset from Kaggle:

https://www.kaggle.com/datasets/hrishitpatil/flight-data-2024

2. Place the dataset file inside the data/ folder

3. Update file paths in the notebooks if necessary

The pipeline will run without modification.


--- 

## Reproducibility

All data cleaning, feature engineering, and EDA steps are fully reproducible using the code provided in this repository.

## Authors 

Helena Li, Crystal Guo, Nikhil Shanbhag, Yijing Zhang
