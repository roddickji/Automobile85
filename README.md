# Automobile Data Cleaning

This repository contains a cleaned version of the **Automobile Data Set** from the [UCI Machine Learning Repository]([https://archive.ics.uci.edu/ml/datasets/Automobile](https://archive.ics.uci.edu/dataset/10/automobile)).

## 📄 Description

The original dataset (`imports-85.data`) is provided in raw `.data` format, with missing values encoded as `"?"` and without column names.  
This repository processes the raw data into a **tidy `.csv` file** with:

- Descriptive column names
- Missing values properly marked as `NA`
- Consistent formatting for further analysis

## 📂 Files

- `Raw/imports-85.data`: Original raw data from UCI
- `Raw/data_into_csv.py`: Python script used to convert and clean the data
- `automobile85.csv`: Cleaned data in CSV format

## 🛠️ Tools Used

- Python (pandas)

## 📊 Dataset Overview

- 26 variables (both categorical and numerical)
- 205 observations

## 🔍 Source

Schlimmer, J. (1985). Automobile [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5B01C.
