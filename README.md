# Task 1: Data Cleaning & Preprocessing
"Preprocessing the House Prices dataset: missing values, encoding, outlier removal, and normalization"

## 🗂 Dataset
- **Name:** House Prices - Advanced Regression Techniques
- **Source:** [Kaggle](https://www.kaggle.com/datasets/camnugent/house-prices-advanced-regression-techniques)
- **File:** `train.csv`

## 📌 Objective
Clean and preprocess the dataset for machine learning models.

## 🔧 Steps Performed
- Loaded data with Pandas
- Handled missing values using:
  - Median for numeric
  - Mode for categorical
  - Dropped columns with excessive nulls
- Encoded categorical features using `LabelEncoder`
- Removed outliers using IQR
- Scaled numerical features using `StandardScaler`

## 📁 Files Included
- `train.csv`: Raw data
- `task1_preprocessing.ipynb`: Full preprocessing script
- `cleaned_house_prices.csv`: Final output
- `README.md`: Summary of this project

## 🚀 Output
Cleaned dataset ready for model training.

## 👤 Author
Shweta Yenaji
