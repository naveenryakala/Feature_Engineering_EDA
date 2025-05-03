# Feature Engineering and Exploratory Data Analysis (EDA)

This project focuses on Feature Engineering and Exploratory Data Analysis (EDA) using various datasets. The aim is to provide a comprehensive understanding of data preprocessing techniques and exploratory analysis methods that are essential for data science projects.

## Project Structure

The project is organized as follows:

```
Feature-Engineering-EDA
├── datasets
│   ├── red_wine.csv
│   ├── flight_price.csv
│   └── google_playstore.csv
├── notebooks
│   ├── handling_missing_values.ipynb
│   ├── handling_imbalanced_dataset.ipynb
│   ├── handling_imbalanced_dataset_smote.ipynb
│   ├── handling_outliers.ipynb
│   ├── data_encoding_one_hot.ipynb
│   ├── label_and_ordinal_encoding.ipynb
│   ├── target_guided_ordinal_encoding.ipynb
│   ├── red_wine_eda.ipynb
│   ├── flight_price_eda_feature_engineering.ipynb
│   ├── data_cleaning_google_playstore.ipynb
│   └── eda_cleaned_google_playstore.ipynb
├── README.md
└── requirements.txt
```

## Datasets

- **Red Wine Dataset**: Located in `datasets/red_wine.csv`, this dataset is used for EDA and feature engineering tasks related to wine quality.
  
- **Flight Price Dataset**: Found in `datasets/flight_price.csv`, this dataset is utilized for analyzing flight prices and performing feature engineering.

- **Google Playstore Dataset**: Available at `datasets/google_playstore.csv`, this dataset is used for data cleaning and EDA on mobile applications.

## Notebooks

The project includes several Jupyter notebooks that cover various topics in feature engineering and EDA:

1. **Handling Missing Values**: Techniques for identifying and managing missing data.
2. **Handling Imbalanced Dataset**: Strategies for addressing class imbalance in datasets.
3. **Handling Imbalanced Dataset using SMOTE**: Implementation of the SMOTE technique to balance classes.
4. **Handling Outliers**: Methods for detecting and managing outliers in datasets.
5. **Data Encoding - Nominal (One-Hot Encoding)**: Demonstration of one-hot encoding for categorical variables.
6. **Label and Ordinal Encoding**: Techniques for encoding categorical data into numerical formats.
7. **Target Guided Ordinal Encoding**: Encoding ordinal variables based on the target variable.
8. **Red Wine Dataset EDA**: Exploratory analysis of the red wine dataset.
9. **Flight Price Dataset EDA and Feature Engineering**: Combined EDA and feature engineering on flight price data.
10. **Data Cleaning with Google Playstore Dataset**: Techniques for cleaning the Google Playstore dataset.
11. **EDA on Cleaned Google Playstore Dataset**: Exploratory analysis on the cleaned dataset.

## Installation

To run the notebooks, you need to install the required Python packages. You can find the list of packages in the `requirements.txt` file. Install them using:

```
pip install -r requirements.txt
```